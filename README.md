# TP1_MLOps
##Partie 1 : Préparation de l'environnement Git
1. Création de clé SSH

<img width="722" height="551" alt="image" src="https://github.com/user-attachments/assets/785e38e5-fa89-4a15-b4c9-8d6ed70337f6" />
<img width="1014" height="269" alt="image" src="https://github.com/user-attachments/assets/8e3a99cc-c406-460b-b12d-51d8b83d8e83" />

2. Configuration de Git


<img width="447" height="85" alt="image" src="https://github.com/user-attachments/assets/2dcf586a-97b1-461f-93a5-43a5d164df0c" />

3. Connexion SSH au dépôt distant
   
<img width="633" height="74" alt="image" src="https://github.com/user-attachments/assets/1b7f44ea-a5a3-49a6-85dd-3a66283bfee1" />

4. Vérifier la configuration actuelle de Git
 Pour afficher ta configuration Git (nom, email, etc.) :

<img width="450" height="70" alt="image" src="https://github.com/user-attachments/assets/76b74f8c-20d1-4210-ad90-1da135a162f6" />

5. Modifier ton adresse e-mail Git

<img width="540" height="60" alt="image" src="https://github.com/user-attachments/assets/626b6a4c-37cc-49bf-af16-0fcdd02e4c83" />

 Pour vérifier le changement :
 
<img width="365" height="52" alt="image" src="https://github.com/user-attachments/assets/8f094976-f7c2-47f3-b7ea-ef8a81ff708a" />

##Partie 2: Création d'un nouveau projet
1. Connexion à votre compte GitHub / GitLab et Création d’un nouveau dépôt:

<img width="1317" height="648" alt="image" src="https://github.com/user-attachments/assets/ef93358d-6987-4e8c-95c6-ee333d710a0e" />
   
2. Copier l’URL SSH du dépôt et Cloner le projet sur votre machine locale :

<img width="560" height="51" alt="image" src="https://github.com/user-attachments/assets/24d057bb-bd88-4d7a-b8db-5c8d54a278a1" />

3. Accéder au dossier du projet:

<img width="530" height="107" alt="image" src="https://github.com/user-attachments/assets/5b197b29-a801-44d2-9495-0bc0328705b7" />

5. Ajouter un fichier README.md après coup

Si vous n’avez pas ajouté de README lors de la création du projet, vous pouvez le faire manuellement :

Étapes :

++Créez le fichier :

$echo "# Fraud Detection MLOps Project" > README.md

(ou ouvrez-le avec un éditeur et ajoutez du contenu)

++Ajoutez le fichier au suivi Git :

$git add README.md

++Faites un commit :

$git commit -m "Ajout du fichier README.md"

++Envoyez les changements sur le dépôt distant :

$git push origin main

(ou master selon la branche par défaut de votre dépôt)






