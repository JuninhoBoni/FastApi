# FastApi

  Projeto desenvolvido em Python3.9

## Objetivo  
  
  API com comunicação aos bancos de dados Oracle e SQL Server

## Instalação do ambiente de desenvolvimento:
  
  Instalar python3.9
    Observar nas opções de instalação, a inserção do python nas variáveis de sistema.
    É recomendado instalar o python com a opção que disponibiliza-o à todos os usuários do Windows, pois desta forma a instalação é realizada no diretório padrão dos programas do Windows.
  
  O ambiente abaixo foi criado a partir do powershell dentro do Visual Studio com as extenções abaixo:
    Magic Python
    Notepad++ keymap
    PowerShell
    Pylance
    Python
    Python Extension Pack
    Visual Studio IntelliCode

  Executar o comando abaixo. Este comando cria o ambiente de desenvolvimento, com isso possibilita instalar somente as bibliotecas necessárias para o projeto, facilitando na compilação.
    python -m venv fastapi
  Executar o comando abaixo para activar o ambiente virtual.
    fastapi\Scripts\activate
  Executar o comando abaixo para instalar as bibliotecas que serão utilizadas no projeto.
    pip install -r requirements.txt
  Ambiente de desenvolvimento criado. É importante notar que qualquer inserção de biblioteca no projeto, é necesário rodar o comando abaixo para atualizar o requirements.txt.
    pip freeze > requirements.txt 
    
## Execução
  
  uvicorn FastAPI:app --reload