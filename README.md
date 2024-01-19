```bash
#Criar ambiente virtual
python -m venv venv 

# Ativar o ambiente virtuual
venv\Scripts\Activate

# Instalar bibliotecas
pip install django
pip install pillow

# Criar umas pasta de projeto
django-admin startproject study_async .

# manage.py é o cli do django
# settings.py é por onde configuramos a aplicação
#Configurar o settings.py
LANGUAGE_CODE = 'pt-br'
TIME_ZONE = 'America/Sao_Paulo'

#Rodar o servidor para testar
python manage.py runserver

#Criar aplicação pyhton
python manage.py startapp usuarios

# Instalar o aplicativo usuarios no settings.pu do core
    INSTALLED_APPS = [
        'usuarios',
    ]

# Configurar as URLS no urls.py
# - Inserir include no final da lina
    - from django.urls import path, include
# - Criar urls.py na pasta usuarios

# https://pythonando.com.br/psw/evento/?identificacao=2
# https://grizzly-amaranthus-f6a.notion.site/AULA-2-16b4cd3a4337482887daa7f5aea2fb31
# Parei no 01:07:37 Flashcard iterativo
