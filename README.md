# Django-Intermediário

Projeto Django-intermediário - curso Geek University


## Projeto apenas para fins **didáticos** não é um projeto **"real"** ##


Desenvolvido com Django 3.0 - Python 3.8 - MariaDB/MySQL 10.1.43

-------------------------------------------------------------------------

## Como rodar o projeto? ##

```
git clone https://github.com/Hp2501/Django_intermediario.git
cd Django_intermediario
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Obs: configurar o *__python-decouple__* e *__dj_database_url__*


[como configurar](https://samuelgoncalves.com.br/configurar-sua-aplicacao-django-para-ler-dados-diferentes-por-ambiente/)


## Conhecimentos aplicados no Projeto ##


* Criação do projeto em Mysql
* Criando as Views
* Criando as rotas
* Criação dos Forms
* Definindo e configurando os Models
* Trabalhando com ModelForms
* Salvando dados no DB
* Apresentando dados do DB no Template
* Tralhando com seções do usuário


## JS - CSS

* [django-bootstrap4](https://pypi.org/project/django-bootstrap4/)

