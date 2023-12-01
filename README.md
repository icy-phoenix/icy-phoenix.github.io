# Site de blog de test

## Environnement

- Outil de suivi de version des sources : Git
- Serveur pour le partage des sources : Github
- Moteur de blog : Jekyll
- Environnement de développement (en ligne): Github codespaces
- Automatisation de la publication du site sur un serveur web : Github Actions
- Hébergement du site web : Github Pages

## Commandes principales

Activer le suivi de fichier par git:

- suivre toutes les modifications faites sur tous les fichiers du répertoire courant (`.`): `git add .`
- suivre les modifications faites sur un fichier en particulier (ex: doc/mon-fichier.txt): `git add doc/mon-fichier.txt`

Enregistrer l'état courant des fichiers suivis avec un message de commentaire: `git commit -m "Ceci est le commentaire qui apparaît dans l'historique des changements"`

Publier l'état enregisté des fichiers: `git push`

Réccupérer l'état enregisté des fichiers publié par d'autre personnes: `git pull`