# Index collaboratif des commandes `git`



## Revenir à la liste des commandes

Pour revenir à la liste complète des commandes, [cliquez ici](index.html)



## Commande `git pull`


### Description

La commande `git pull` est utilisée pour faire un fetch du contenu d'un dépôt distant et pour le télécharger, puis pour mettre à jour immédiatement le dépôt local qui correspond à ce contenu.

### Exemples

```
 Options communes

git pull <remote>

Fetch the specified remote’s copy of the current branch and immediately merge it into the local copy. This is the same as git fetch ＜remote＞ followed by git merge origin/＜current-branch＞.

git pull --no-commit <remote>

Comme l'invocation par défaut, fait un fetch du contenu distant mais ne crée pas de nouveau commit de merge.

git pull --rebase <remote>

Comme dans le pull précédent, au lieu d'utiliser git merge pour intégrer la branche distante avec la branche locale, utilisez git rebase.

git pull --verbose

Fournit une sortie « verbose » lors d'un pull qui affiche le contenu téléchargé et les détails du merge.