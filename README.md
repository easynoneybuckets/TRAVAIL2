DEPOT TEST SUR L'UTILISATION DE GIT/GITHUB

1. TELECHARGER GIT:

WINDOWS: https://git-scm.com/downloads
MAC: - Git est déjà installé. 
     - Si vous faites face à une erreur de licence; éxécutez cette commande sur votre terminal: sudo xcodebuild -license

2. APRES INSTALLATION, Ouvrez votre terminal et testez la version:
git --version

3. CONFIGURATION DU PROFIL/BASE GIT (Ne se fait qu'une seule fois):
   
git config --global user.name "Ton Nom"
git config --global user.email "tonemail@example.com"

4. CREATION D'UN PROJET
   
A. SI TU AS DEJA UN DOSSIER+FICHIER (GIT)
   
         ** EXEMPLE TERMINAL ** (executez ces commandes une par une)
        cd mon-projet (pour acceder au dossier mon-projet déjà crée manuellement) 
        git init
        git add nomdufichier.docx (pour ajouter le fichier nomdufichier.docx sur git)
        git add . (pour ajouter le tous les fichier disponibles dans mon-projet sur git)
        git commit -m "Ajout de la fonctionnalité X" (pour enregistrer un changement avec un message)
   
B. CREER LE DEPOT SUR GITHUB

     Va sur GitHub :

     👉 https://github.com/new
     -Crée un compte
     -Remplis les informations demandées 

        Repository name: TRAVAIL 2
        Description : Audit complet cybersécurité – Ecommerce Express
        Public ou Private selon ton choix
        NE PAS cocher README, .gitignore ou License (si on les a déjà, si vous ne les avez pas cochez OUI !!)
        Clique Create repository.

      GitHub va t’afficher une page avec des instructions.

C. COPIER DEJA UN PROJET EXISTANT (NOTRE CAS)
   
     ** EXEMPLE TERMINAL **
     cd downloads
     git clone https://github.com/utilisateur/projet.git (pour télécharger le dépôt localement)
     git push (pour envoyer le changement sur github)


     
