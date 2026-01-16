# Documentation du tuto Github avec Git

## Initialisation du dépot

```
git init
git remote add origin https://github.com/JugurthaHK/TestGit-Github.git
git status
git add README.md
git push -u origin master
```

## Rédiger un commit

```
Titre du commit

Déscription du commit avec les infos sur l'evolution du projet
```

## Tout ce qui à un rapport avec les branches

```
Ajouté par : Jugurtha | Branche : develop
git branch
git checkout -b nomBranche
git checkout nomBranche
git branch -b nomBranche
```

Pour les bonnes pratiques, on va intégrer la notion de revue de code. Pour cela on va créer une branche, faire des modifications, les envoyer sur le depot distant, puis créer une pull request pour demander une revue de code.
