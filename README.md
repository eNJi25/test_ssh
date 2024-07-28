# Documentation du test Github avec Git

## Initialisation du projet

```bash
git init
git remote add origin URL_SSH_DEPOT
```

## Rédiger un commit

```
Titre du commit

Description de notre commit avec des informations sur
l'évolution du projet
```

## Envoyer un commit sur le dépôt distant

```bash
git add .
git commit -m "Titre du commit"
git push origin main
```

## Création d'une branche

```bash
git checkout -b NOM_BRANCH
```
Pour les bonnes pratique, on va intégrer la notion de revue de code. Pour cela, on va créer une branche, faire des modifications, les envoyer sur le dépôt distant, puis créer
une pull request pour demander une revue de code.