# Dicas Kindle para Windows

Veja todos os detalhes assistindo ao vídeo: 



## Como remover o DRM dos ebooks baixados da Amazon

### 1. Instalar Python 2.7 

Acessar https://www.python.org/downloads/release/python-2715/ , 
baixar instalador para Windows [**Windows x86-64 MSI installer**](https://www.python.org/ftp/python/2.7.15/python-2.7.15.amd64.msi)
e instalar o Python. Não esquecer de marcar opção que também instala o **pip**.

### 2. Instalar Microsoft Visual C++ Compiler for Python 2.7 

Este pacote é necessário para rodar o plugin/script de remoção do DRM.

Baixar o instalador direto do site da Microsoft ( https://www.microsoft.com/en-us/download/details.aspx?id=44266 ) e instalar normalmente.

### 3. Baixar e descompactar o DeDRM_tools

Acessar a página de releases do projeto (DeDRM_tools)[https://github.com/apprenticeharper/DeDRM_tools]: https://github.com/apprenticeharper/DeDRM_tools/releases

Baixar o zip da última versão (recomendo uso da versão DeDRM_tools_6.6.1.zip) e descompactar em local de preferência.

### 4. Baixar e executar script de verificação e execução do DeDRM 

Baixar [este arquivo](https://raw.githubusercontent.com/matheusmota/dicas-kindle/master/resources/abrir-dedrm.bat) que facilita a execução do DeDRM e salvar **na mesma pasta descompactada** do DeDRM. 
(exemplo: se você descompactou o arquivo DeDRM_tools_6.6.1.zip na pasta DeDRM_tools_6.6.1, salve o arquivo dentro desta pasta )

### 5. Executar o DeDRM 

Com o botão direito do mouse clique sobre o arquivo **abrir-dedrm.bat** salvo dentro da pasta descompactada. Em seguida escolha "executar como administrador" e faça a remoção do DRM.

