# Commandes git

Liste des commande git

## git init
- Permet d'initialiser un répertoire

## git add
- Permet d'ajouter un fichier ou des modifications dans le satgging

## git commit 
- Permet d'enregistrer une modification en local
- Le message est important

## git push
- Permet de pousser les modofocations en ligne(sur github)

## git status
  - Permet de vérifier le statut du répertoire
  - Permet de lister les modifications à traiter

## git log
- Permet de lister les modifications en local

## git log --oneline
Permet de donner des éléments de manière compacte

## git branch + [nom de la branche]
- Permet de créer une branche
- Exemple: git branch feature/code-html

## git branch
- Permet de voir la liste des branches.

## git checkout
- Permet de se déplacer d'une branche à une autre

## git checkout -b 
- Permet de créer et de se déplacer dans une branche si elle n'existe pas
- Exemple: git checkout -b feature/code-css

## git pull
- Permet de recuperer les modifications distantes

## git rebase
- Permet de recuperer les modifications dans la branche mère
- Les modifications de la branche mère sont placées en dessous des modifications de la branche courante
- Les modifications de la branche courante sont placées au dessus des modifications de la branche mère.


## git reset
- Permet de supprimer un commit
- Permet de revenir à un commit défini par son identifiant
- Attention à utiliser avec précaution

## git diff
- Permet de comparer eux commits

## git clone
- Permet de recupérer un projet existant. 
- On copie le lien dans github et dans le terminal on fait git clone + lien
