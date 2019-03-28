# Dicas Kindle para Linux

Veja todos os detalhes assistindo ao vídeo: https://www.youtube.com/watch?v=KLTypN4h8hU&t=9s&list=PLvsEcgwfG2GFjN0SEqfu6L7HFDOmXSgpU&index=6


## Como remover o DRM dos ebooks baixados da Amazon


### 1. Instalar o Python 2, pip e tk :
```bash
sudo apt-get install -y python-pip python-tk 
```

### 2. Instalar bibliotecas necessárias ao DeDRM

```bash
sudo pip2 install -U pip
sudo pip2 install pycrypto==2.6.1 pylzma
```

### 3. Baixar e descompactar o DeDRM_tools

Acessar a página de releases do projeto [DeDRM_tools](https://github.com/apprenticeharper/DeDRM_tools): https://github.com/apprenticeharper/DeDRM_tools/releases

Baixar o zip da última versão (recomendo uso da versão DeDRM_tools_6.6.1.zip) e descompactar em local de preferência.

Caso prefira, os comando abaixo instalam os programas necessários, baixa o DeDRM e descompacta em uma pasta :
```bash
sudo apt-get install -y wget zip
wget https://github.com/apprenticeharper/DeDRM_tools/releases/download/v6.6.1/DeDRM_tools_6.6.1.zip
unzip DeDRM_tools_6.6.1.zip -d DeDRM_tools_6.6.1
cd DeDRM_tools_6.6.1
```

### 4. Abrir interface do DeDRM para remover o drm dos arquivos (seguir instruções do vídeo)

Dentro da pasta do DeDRM:
```bash
python2 DeDRM_Windows_Application/DeDRM_App/DeDRM_lib/DeDRM_App.pyw
```

### Importante

Usar Python2 (versão 2.7) e o pip para Python2.

