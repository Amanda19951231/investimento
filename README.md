# PSW 11
 
Criar ambiente virtual
	# Windows
		python -m venv venv

Depois de criado para ativar
	# Windows
		venv\Scripts\Activate

# Caso algum comando retorne um erro de permissão execute o código e tente novamente:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

Instalação do Django e das demais bibliotecas:

pip install django
pip install pillow

Vamos criar o nosso projeto Django: (. serve para ser no mesmo diretório)
django-admin startproject core .
​
Rode o servidor para testar:
python manage.py runserver