# Symfony6-docker

Starter kit pour applications Symfony - maj juillet 2024

## Specifications:
- php 8.3
- symfony 6.4
- postgresql 16

## Utilisation :
- make install : build des images docker, composer install, npm install et build assets
- make start : démarrage des images php, nginx et postgresql
- make stop : arrêt des containers du projet
- make connect / node-connect : shell dans les containers php / nodejs
- make clear : vidage du cache
- make composer-update : mise à jour des vendors php
- make node-install : installation des vendors js
- make node-build : compilation des assets js et scss

- url par défaut en mode dev : http://localhost:8081