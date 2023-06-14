# git

crée un repertoire de projet local

    git init .

recuperé un projet depuis un repertoire github ou autre

        git clone https://github.com/redhox/git.git


ajoutée des fichier ou dossier a commit au projet

    git add nom fichier
ou tout le dossier

    git add .

commit au projet 

    git commit 
    
 commit avec un message 
  
    git commit -m "first commit c_est le message"
 
 
 voir les commit
 
    git log
 
 les commit on un code qui peu etre utilisé pour recuperé l'etat du code au moment du commit
 
    git checkout [code du commit]
 
 
 crée une nouvelle branche 
 
    git branch
    
 changer de branche active
    
    git checkout
    
 crée une brache et en faire la brache active en meme temps
 
        git checkout -b ma-nouvelle-branche
    
 état actuel du projet 
 
    git checkout main
    
  merge des branche
      
      git merge nom_de_la_branche_a_merge
  suprimer une branche
      
      git branch -d 
      
  visualisation grafique du projet
  
    git log --graph --oneline --decorate --all
    
 connecté sont git a sont compte github , installer 'gh' , executé la comande puis suivez les instruction
        
        gh auth login
   
    
  pour connecté le projet a un repertoire github
  
        git remote add origin https://github.com/nom-d'utilisateur/nom-du-repo.git
envoyer les commit sur le repertoire en ligne 

        git push origin main
recuperé les modifocation fait au projet en ligne 

        git pull origin main
        
 
        

     
      
  
