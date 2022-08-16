# IngenieriadeSoftware
Practicos Ingenierira
- docker-compose up -d --build
- sudo docker ps 
- sudo docker exec -ti  89d531a3d96b mysql -p -u bn_myapp
- create database practico (si no existe)
- sudo docker exec  -ti c2942d4684be  /bin/bash 
- php artisan migrate
# Crear el proyecto desde la imagen
- -sudo docker run -ti --rm -v $(pwd):/app ggmartinez/laravel:9-php7 createProject

