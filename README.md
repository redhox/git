# git

<h2> en local </h2>

geré le nom de la branche principale pour git

    git config --global init.defaultBranch main

.
 
    
    git config --global user.name "VotreNom"
    git config --global user.email "votre@adresse.email"


crée un repertoire de projet local

    git init .

ou recuperé un projet depuis un repertoire github ou autre

        git clone https://github.com/redhox/git.git


ajoutée des fichier ou dossier a commit au projet

    git add nom fichier
ou tout le dossier

    git add .

pour ignoré un fichier ou un dossier il nous faut un fichier  .gitignore
dans le quelle je nomme les dossier et fichier a ignoré 
        
        dossier_ignoré/
        fichier_igionré

commit au projet 

    git commit 
    
 commit avec un message 
  
    git commit -m "first commit c_est le message"
 
 
 voir les commit
 
    git log
 
 les commit on un code qui peu etre utilisé pour recuperé l'etat du code au moment du commit
 
    git checkout [code du commit]
 
 <h2> gestion des branch </h2>
 
 crée une nouvelle branch
 
    git branch
    
 changer de branch active
    
    git checkout
    
 crée une branch et en faire la branch active en meme temps
 
        git checkout -b ma-nouvelle-branch
    
 état actuel du projet 
 
    git checkout main
    
  merge des branch
      
      git merge nom_de_la_branch_a_merge
  suprimer une branch
      
      git branch -d 
  

    
  <h2> connection avec github </h2>

    
 connecté sont git a sont compte github , installer 'gh' , executé la comande puis suivez les instruction
        
        gh auth login
   
    
  pour connecté le projet a un repertoire github
  
        git remote add origin https://github.com/nom-d'utilisateur/nom-du-repo.git
envoyer les commit sur le repertoire en ligne 

        git push origin main
recuperé les modifocation fait au projet en ligne 

        git pull origin main
        
   <h2> bonnus pour la route </h2>

visualisation grafique du projet
  
    git log --graph --oneline --decorate --all

     
      
  
