# Application des surnoms des enseignants - Step 0

## Générer le projet de départ

Dans cette étape, nous allons simplement exécuter la commande initiale qui permet de générer un projet AodnisJS.

```bash
npm init adonisjs@latest app-teachers-adonisjs -- --kit=web --db=mysql --auth-guard=session
```

`app-teachers-adonisjs` est le nom du projet.

`--kit=web` permet de spécifier que nous souhaitons créer une application web de rendu serveur traditionnelle.

`--db=mysql` permet de spécifier le SGBDR souhaité, dans notre cas MySQL.

`--auth-guard=session` permet de spécifier le garde d'authentification, à savoir session, qui est basé sur les sessions et les cookies.

Nous obtenons une arborescence complète de fichiers et répertoires.

<img src="./doc/images/arborescence.png" style="width: 10%">

Pas de panique ! Vous allez rapidement vous retrouvez dans tous ces fichiers.

## Installation des extensions de vscode

Nous allons installer 3 extensions :

- AdonisJS Extension

<img src="./doc/images/extension-vscode-adonisjs.png" style="width: 30%">

C'est l'extension officielle vs-code pour le framework AdonisJS.

- Edge template

<img src="./doc/images/extension-vscode-adonisjs-edge-template.png" style="width: 30%">

Le gestionnaire de template d'AdonisJS est Edge. Cette extension offre la coloration syntaxique Edge pour Visual Studio Code.

- Prettier - Code formatter

Fomater votre code avec Prettier

## Prochaine étape

Dans la prochaine étape <a href="https://github.com/GregLeBarbar/app-teachers-adonisjs/tree/step1">step1</a>, nous allons modifier la vue `home` et gérer les fichiers statiques CSS et JS.
