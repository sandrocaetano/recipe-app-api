# recipe-app-api
Recipe API Project

# Criando o projeto app
docker-compose run --rm app sh -c "django-admin startproject app . "

# Verificando a sintaxe do Python
docker-compose run --rm app sh -c "flake8"

docker-compose run --rm app  sh -c "python manage.py startapp core"