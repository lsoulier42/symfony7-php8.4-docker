# Symfony7-php8.4-docker

Starter kit pour applications Symfony

## Specifications:
- php 8.4
- symfony 7.2
- postgresql 16

## Utilisation :
- make install : build des images docker, composer install et build assets
- make start : démarrage des images php, nginx et postgresql
- make stop : arrêt des containers du projet
- make connect / node-connect : shell dans les containers php / nodejs
- make clear : vidage du cache
- make composer-update : mise à jour des vendors php

- url par défaut en mode dev : http://localhost:8081