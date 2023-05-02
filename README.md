# Billed
SaaS RH de gestion de notes de frais
Formation OpenClassrooms
Développeur d'applications JavaScript React

## L'architecture du projet :
Ce projet, dit frontend, est connecté à un service API backend que vous devez aussi lancer en local et qui se trouve dans le meme depot.


## Copier le code frontend et backend :

git clone https://github.com/Merite15/Billed-app-FR-Front

## Ouvrir chaque dossier dans un terminal différent :

## Terminal 1:
$ cd Billed-app-FR-Back
$ npm i
$ npm i -g sequelize
$ npm i -g sequelize-cli
$ npm i -g jest
$ npm install -g win-node-env
Ouvrir le fichier « package.json » et ajouter les commandes suivantes SANS ESPACE AVANT "&&"

"test": set NODE_ENV=test&& sequelize-cli db:migrate&& jest test -i tests/user.test.js --watch
"run:dev": "set NODE_ENV=development&& sequelize-cli db:migrate&& node server.js

## Pour lancer le back:

npm run run:dev

## Terminal 2:
$ cd Billed-app-FR-Front
$ npm install
$ npm install -g live-server
Pour lancer le front:

$ live-server
Si le site n’est pas lancé automatiquement : Ouvrir le navigateur à l'adresse: http://127.0.0.1:8080/


## Comment lancer tous les tests en local avec Jest ?
npm run test


## Comment lancer un seul test ?
Installez jest-cli :

$ npm i -g jest-cli
$ jest src/__tests__/your_test_file.js


## Comment voir la couverture de test ?
http://127.0.0.1:8080/coverage/lcov-report/

## Comptes et utilisateurs :
Vous pouvez vous connecter en utilisant les comptes:

administrateur :
utilisateur : admin@test.tld
mot de passe : admin
employé :
utilisateur : employee@test.tld
mot de passe : employee