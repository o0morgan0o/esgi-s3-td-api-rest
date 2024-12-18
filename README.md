# Création d'une API en PHP


## Objectifs

- Créer une API REST basique en PHP

Vous avez dans ce repo une base de données sqlite appelée 'users.sqlite' contenant une table 'users' avec les champs suivants :

- id (int) clé primaire 
- first_name (text) Prénom
- last_name (text) Nom
- email (text) Email
- avatar (text) URL de l'avatar

Nous allons créer une API Rest pour gérer ces utilisateurs.


## Exercices

1. Créer le point d'entrée de l'API pour récupérer la liste des utilisateurs

GET /api/users -> doit retourner un json contenant la liste des utilisateurs

2. Créer le point d'entrée de l'API pour récupérer un utilisateur

GET /api/users/{id} -> doit retourner un json contenant les informations de l'utilisateur

3. Créer le point d'entrée de l'API pour ajouter un utilisateur

POST /api/users -> doit ajouter un utilisateur dans la base de données et retourner un json contenant les informations de l'utilisateur ajouté

4. Faire un sorte que le création de l'utilisateur génère un avatar aléatoire

