# status
Dans Github, le statut (status en anglais) est une fonctionnalité qui permet de savoir si une intégration ou une construction de code a réussi ou échoué.
En résumé, le statut dans Github est une fonctionnalité utile pour suivre l'état des intégrations et des constructions de code, ce qui permet aux développeurs de détecter rapidement les problèmes et de les corriger avant qu'ils ne deviennent des problèmes plus graves pour le projet.
# clone
`git clone` permet de récupérer un dépôt Git distant et de l'avoir localement. Par exemple, `git clone git@github.com:CIN-A/CIN-A.git` va chercher le dépôt https://github.com/CIN-A/CIN-A et crée un dossier `CIN-A` avec son contenu.
# push
# pull/fetch
![](https://campusmaps.umn.edu/sites/campusmaps.umn.edu/files/styles/circle_pic/public/2019-09/SpongeBob-square.png?itok=cbHih9qs)


# **Commandes Git**

*- Les termes "pull" et "fetch" sont couramment utilisés dans le contexte de Git et de GitHub pour se référer à deux actions distinctes, mais liées, qui sont effectuées lors de la collaboration avec un dépôt distant (remote repository) sur GitHub.*

>**Pull**
>
>D'autre part, la commande "pull" permet de récupérer les dernières modifications effectuées sur le dépôt distant et de les fusionner automatiquement avec votre code existant dans votre branche locale. Cela signifie que les modifications récupérées seront immédiatement intégrées à votre code existant sans que vous ayez à les examiner avant de les fusionner.
>

>**Fetch**
>
>
>La commande "fetch" permet de récupérer les dernières modifications effectuées sur le dépôt distant et de les intégrer dans votre dépôt local sans fusionner ces modifications avec votre code existant. Cela signifie que les modifications récupérées ne sont pas encore intégrées à votre branche locale et que vous pouvez les examiner avant de décider de les fusionner avec votre code.

En résumé, la commande "fetch" permet de récupérer les modifications du dépôt distant pour les examiner avant de les fusionner, tandis que la commande "pull" permet de récupérer et de fusionner automatiquement les modifications avec votre code existant
# merge
# rebase
# reset
# branch
Une branche permet de travailler sur une fonctionnalité sans risquer de corrompre les fonctionnalités fonctionnelles.
git branch                        -> Donne la liste des branches du répo
git branch Nouvelle branch        -> Crée une branch avec le nom "Nouvelle branch"
# checkout
sert à changer de branche 
git checkout ＜nom de la branche＞

l'argument -b permet de crée la branche et de automatiquement switch dessu en se basant sur la branche ou on se situe au moment de la commande
git checkout -b ＜nouvelle-branche＞

on peut préciser sur quelle branche on se base
git checkout -b ＜nouvelle-branche＞ ＜branche-existante＞

# log
# commit
Les commits peuvent être considérés comme des instantanés ou des étapes importantes dans la chronologie d'un projet Git. Ils sont créés grâce à la commande "git commit" pour capturer l'état d'un projet à un point dans le temps.
Par exemple, "git commit -m "first commit" (-m signifie le message du commit)
