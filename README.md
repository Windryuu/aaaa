# mysql-docker

Infra deliwrapp pour le sgbd MySql

 ### Getting started
Cloner le projet à la racine de ce projet

git clone ...

Ensuite executer la commande, pour initialiser tous les containers

docker-compose up -d

OU bien

docker-compose up


Mise en place de la bdd
Rentrer dans le docker de l'app

docker exec -it php-fpm bash

Executer la commande

php bin/console migration:migrate


Executer l'app
Dans un navigateur entre l'url "localhost:8741"
