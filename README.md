# ML
Machine Learning Introduction 

git config --global user.name "MarkoBrie" 
git config --global user.email marko.briesemann@gmail.com

git config --list


git push -u origin main

password authentication has been removed in 2021
https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token

Generate New Token
https://github.com/settings/tokens?type=beta

git remote -v
git remote remove origin

  git add .
  git commit -m “Modification du titre H1”
  git push origin main
  
-- correct changes
  git commit --amend -m "Votre nouveau message de commit" 
  
-- you forget to add a file
  git add FichierOublie.txt
  git commit --amend --no-edit

git branch
git branch <name of new branch>
  
  pour basculer sur une autre branch
  git checkout cagnotte
  git commit -m “Réalisation de la partie cagnotte côté front end”
  git push origin cagnotte
  git checkout main
  git merge cagnotte
 
-- get main branch updates
  git pull origin main

  git branch -d permet de supprimer une branche.

git status permet de voir l’état des fichiers.

git stash enregistre les modifications non indexées pour une utilisation ultérieure. 

git log affiche l'historique des commits réalisés sur la branche courante.

git reset --hard HEAD^ permet de réinitialiser l'index et le répertoire de travail à l'état du dernier commit.

git commit --amend permet de sélectionner le dernier commit pour y effectuer des modifications.
  
  git log affiche l'historique des commits réalisés sur la branche courante.

git reflog est identique à git log. Cette commande affiche également toutes les actions réalisées en local.

git checkout un_identifiant_SHA-1 permet de revenir à une action donnée.

git blame permet de savoir qui a réalisé telle modification dans un fichier, à quelle date, ligne par ligne.

git cherry-pick un_identifiant_SHA-1 un_autre_identifiant_SHA-1 permet de sélectionner un commit et de l'appliquer sur la branche actuelle. 
