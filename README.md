# Fruit sort using Deep Learning - Backend - REST API

Projet de classification d'image de fruit : 
- Pas assez mure
- Bon
- Trop mure

Ce projet a été réalisé dans le cadre d'un workshop à l'EPSI Montpellier : l'IA au service de l'industrie

Il s'agit de la partie API qui effectue des prédictions en utilisant notre modèle entrainé.

Projet sur l'entrainement du modèle : https://github.com/joconte/fruit-classifier
Projet sur le front-end : A ajouter

# Outils utilisés
- FastAI
- Starlette
- Heroku

# Groupe de travail
- JACQUES Nils
- SEVRAIN Florian
- LASPOUGEAS Thomas
- CONTE Jonathan

# Site web
API accessible ici : https://fruit-recognizer.herokuapp.com/

Routes : 
- POST - /upload - param : file
- GET - /classify-url - query param : url
