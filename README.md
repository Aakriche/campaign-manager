

###  Lancer le container Docker

A la racine de votre projet, lancer la commande suivante.

```
docker-compose up -d
```

La 1ère fois, cela prendra un certain temps, car Docker va télécharger l'ensemble des images nécessaires à la création de vos containers (Ceux-ci sont configurés dans le fichier **docker-compose.yml**)

Si vous obtenez une erreur (notamment sur Linux), il se peut que vous n'ayez pas les bons droits, utilisez donc la commande **sudo**.

```
sudo docker-compose up -d
```

### Connectez-vous à votre docker

Pour cela connectez-vous en SSH pour entrer à l'intérieur de votre docker

```
docker-compose exec php sh
```

