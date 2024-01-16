# 2024

Recueil des projets du cours synthèse en technique d'intégration expérience interactive finissants TIM 2024

## cloner le repos

```
git clone 
```

## init le repos

```
git submodule init
git submodule update
```

## Pour ajouter un projet 

### utiliser submodule 

```
git submodule add [repository via http] projets/[nom-du-git]
```

### Mettre à jour 

```
git pull --recurse-submodules
```
ou 
```
cd [projets/le-projet]
git pull
```

test



<!-- 
### utiliser subtree?

```
git subtree add --prefix  projets/66B-modele_de_projet git@github.com:tim-montmorency/66B-modele_de_projet.git main --squash
```

## pour mettre a jour un projet
```
subtree pull --prefix  projets/66B-modele_de_projet git@github.com:tim-montmorency/66B-modele_de_projet.git main  --squash
``` -->
