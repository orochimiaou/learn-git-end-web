Voci les commandes de bases pour git

#gestion du depot

git clone <url:ssh/https>  --> cloner un debpot distant en local (côpie)

git fetch -> recupere un maximum d'info du depot (branches)

#branches

git branch -> lister les branches
git checkout <branche> -> se deplacer sur une branche existente
git checkout -b <branche>  ->cree et se deplacer sur une nouvelle branche

git status -> donne l'etat de la branche actuelle

git pull -> viens recuperer les changements depuis le remote sur le local

#commits
#apres une/des modifcation(s) vous pouvez ajouter ces/cette modification(s) et la docummmenter (messages), pour ensuite la/les mettre en ligne

git add <fichier> -> ajouter le fichier nouvellement crée ou modifier au prochain commit 
git commit -m "message" -> créer le commit avec les ajouts précendets accompagnée d'un message
git push -> pousser le comit en ligne

git push --set-upstream origin <remote-branch> -> pour une branche nouvellement crér, il faut la connecter au remote

