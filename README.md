## Documentation du tuto Github avec Git

## Source

[S/0](https://youtube.com/playlist?list=PLdKVEanRftb-H1p8ar5gt7EBPixFlVt-y&si=MlMrHkxdB6aVXAdv)

## Initailison du dépot

```bash
git init
git remote add origin SSH_REPO
```

## Rédiger un commit

```
Titre du commit

Description de notre commit avec des informations sur l'évolution du projet
```

## Envoyer un commit sur le depot distant

```bash
git add .
git commit -m "Titre du commit"
git push origin main
```

## Création d'une branche

```bash
git checkout -b NOM_BRANCHE
```

Pour les bonnes pratique, on va inégrer la notion de revue de code. Pour cela, on va créer une branche, faire des modifications, les envoyer sur le depot distant, puis créer une pull request pour demander une revue de code
