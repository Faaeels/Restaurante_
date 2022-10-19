# Django Rest Framework - Restaurante

API Rest criada juntamente com a Alura ! 

## 🔨 Funcionalidades do projeto

API Rest que disponibiliza uma lista de pizzas [nome, descricao, preço e imagem];

Novas pizzas podem ser adicionadas pelo Django Admin.  
O armazenamento das imagens é realizado em um bucket na S3.

Deploy da API feita no <a href="https://drf-alura-pizza.herokuapp.com/">Heroku</a>

## ✔️ Técnicas e tecnologias utilizadas

- `Python`
- `Django`
- `Django Rest Framework`
- `Heroku`
- `S3`

## 🛠️ Abrir e rodar o projeto:

- python3 -m venv ./venv - crie um ambiente virtual
- source venv/bin/activate - ative seu ambiente virtual 
- pip install Django - instale o django
- pip install djangorestframework - instale o Django Restfremework
- pip install dj-database-url - instalar o database
- pip install dj-static - "irmão" do database
- pip freeze > requirements-dev.txt - mostrar tudo que foi instalado
- -r requirements-dev.txt 
- heroku login - login no heroku 
- heroku open - abrir o heroku 
- git branch - ver todas as branchs no Heroku
- python manage.py createsuperuser
- python manage.py startapp restaurante - criar a pasta restaurante 
- py manage.py makemigrations
- py manage.py migrate
- python manage.py runserver - comando para rodar o server
