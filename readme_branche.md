## Les branches d'un repo git

Il est de bonne pratique de travailler sur le branch principal qui est dédié à la production.
Les branches de développement permettent de faire évoluer le repo sans endommager le code pricnipal.

1. Création d'une nouvelle bracnhe *dev* et basculer dessus
```git checkout -b dev```

2. La commande *git branch* renvoie
```
* dev
  main
```

3. Pour pousser cette nouvelle branche, le premier push se faut avec :
```git push -u origin dev```

4. Ensuite, si on modifie, il n'y a qu'un push simple à faire au final :
 ```git commit -a -m "modif"```
 => ma bracnhe dev est mise à jour