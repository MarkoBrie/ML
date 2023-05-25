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
