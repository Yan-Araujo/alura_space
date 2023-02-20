# Primeiros passos com Django: #

## Instalação e Primeiro Uso:
    - Requisitos: Termos instalado o Python3, pip e o virtualenv sendo esse último instalado via pip com o comando:
      - pip install virtualenv

    - Criar um diretório onde será executado o projeto
  
    - Criar um ambiente virtual com o seguinte comando:
      - virtualenv venv
  
    - Após criado o ambiente virtual, temos que ativa-lo e para isso podemos utilizar o comando:
      - No Mac: source venv/bin/activate

    - Criado o ambiente, temos que instalar o django através do comando:
      - pip install django

    - Sempre que instalarmos um novo pacote, é uma boa prática salvar essas informações em um arquivo chamado requirements.txt através do comando:
      - pip freeze > requirements.txt

    - Podemos usar o comando: "django-admin help" para vermos os comandos disponiveis com o framework

    - Para iniciarmos nosso projeto: Utilizamos o comando startproject + nome do diretorio:
      - django-admin startproject setup .

    - Após isso, alem do diretório, será criado um arquivo chamado manage.py e ele será usado para rodarmos o servidor. Usamos o seguinte comando para isso:
      - python manage.py runserver



