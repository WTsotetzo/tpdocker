Pour lancer le projet, il faut lancer les commande suivante:

-docker build ./
-docker compose build
-docker-compose up -d

Voici ici quelque commande pour utiliser symfony:
-docker-compose exec php composer install
-docker-compose exec php php bin/console doctrine:schema:create

pour stopper les images, utiliser la commande suivante:
-docker-compose stop

Tsotetzo Willy
