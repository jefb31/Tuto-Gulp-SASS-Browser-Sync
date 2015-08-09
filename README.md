# Tuto-Gulp-SASS-Browser-Sync

## Prérequis

##### Installer NodeJS
Suivre les instructions sur https://nodejs.org/download/ (il faut pouvoir lancer la commande `npm` depuis ton terminal)

##### Installer Gulp globalement
`npm install --global gulp`

## Installation

##### Uniquement la première fois pour "configurer" le projet
1. `git clone https://github.com/konpa/Tuto-Gulp-SASS-Browser-Sync.git`
2. `cd Tuto-Gulp-SASS-Browser-Sync`
3. `npm install`

##### A chaque fois que tu veux travailler dessus
1. `gulp` (depuis la racine de ton dossier Tuto-Gulp-SASS-Browser-Sync)
2. Une page s'ouvre automatiquement qui s'actualisera toute seule quand tu modifieras tes fichiers .scss ou .html
3. Modifie ton fichier dist/index.html et/ou tes fichiers .scss dans le dossier src/

Dans le dossier dist se trouvent tous les fichiers de "production", c'est à dire que tu mettras sur ton serveur. Le fichier main.css et généré automatiquement par gulp à chaque fois que tu modifies les fichiers .scss.

Dans le dossier src se trouvent tous les fichiers .scss que tu n'utilises que pour le développement. 

Voilà, n'hésites pas à me poser des questions si tu rencontres des problèmes, nottament sur windaube ;) Que tu maitriseras ça, je te montrerais plein d'autres choses que tu peux faire avec gulp :) (ou tu pourras le découvrir par toi même)
