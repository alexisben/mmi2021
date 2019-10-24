# mmi2021


## GIT CheatSheet : 

### Basics

#### Obtenir la dernière version depuis la remote (le repo sur github)

```
git pull
```
> Vous pouvez avoir un "failed" quand vous voulez pull : c'est surement que vous avez des modifications en local qui ne sont pas "commit", il faut alors créer un commit (sans avoir à le push)

Dans certains cas il peut y avoir des conflits lors du pull. Deux possibilités : 
  - Git résout seul le conflit : dans ce cas il va vous ouvrir une fenêtre pour ajouter un message au commit qu'il créé : soit dans un editeur de texte, soit dans la fenêtre de votre terminal via l'editeur VI. 
  Dans le cas de la fenêtre de l'editeur VI : vous pouvez sauvegarder et quitter l'editeur VI en tapant sur la touche "ESC" - pour quitter le mode édition, puis taper ```:wq``` puis entrée (w - save | q - quit).
  - Sinon vous devez résoudre manuellement le conflit : ouvrir le fichier ou les fichiers en questions, modifier le code en triant les modifications locales (HEAD) VS modifications remote (long identifiant chelou genre ```862638ad1cb8a0d1c30bbb84ab650d5f71bd0cc5```).
  N'oubliez pas de supprimer les balisages git : ```>>>>>> HEAD```, ```=======```, et ```>>>>>>> id du commit distant```



#### Vérifier l'état actuel du projet git en local (sur sa machine)

> Status présente les informations sur l'état actuel du projet en local (suis-je à jour ? Ai-je de nouveaux fichiers non "trackés" - untracked files ? Ai-je des fichiers modifier à commit ?)

```
git status
```

#### Envoyer ses modifications 

> Ajoute les modifications des fichiers, les suppressions et les créations de nouveaux fichiers :

```
git add .
```

> Créer un nouveau "commit" - ceci passe en "Staged" les modifications, les suppressions et les créations de fichiers :

```
git commit -m 'enter what you did here'
```

> Envoyer votre / vos commits sur la remote (Le repo sur Github) : 

```
git push
```



## Links : 

### Tech:

https://experiments.withgoogle.com/

https://tympanus.net/codrops/

https://developer.mozilla.org/fr/

https://codepen.io/

http://caniuse.com


### Créa:

https://dribbble.com/

https://www.behance.net/

http://www.fubiz.net/


### Les deux : 

https://www.awwwards.com/

https://thefwa.com

https://usepanda.com/app/#/

