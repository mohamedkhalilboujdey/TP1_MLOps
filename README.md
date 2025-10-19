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

4. Ajouter un fichier README.md après coup

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

5. Définir un dépôt distant (si oublié)

++Si vous avez créé un projet local sans lier de dépôt distant, vous pouvez le faire après coup avec :

$git remote add origin https://github.com/mohamedkhalilboujdey/TP1_MLOps

++Vérifiez que le lien est bien configuré :

$git remote -v

++Vous devriez voir :

$origin  https://github.com/mohamedkhalilboujdey/TP1_MLOps(fetch)

$origin  https://github.com/mohamedkhalilboujdey/TP1_MLOps(push)

++Ensuite, poussez votre projet vers GitHub :

$git push -u origin main

##Partie 3 : Concepts de base de Git
1. Travailler avec les fichiers

   a. Créer un fichier Python

<img width="488" height="47" alt="image" src="https://github.com/user-attachments/assets/5eeee294-bc6e-44d6-af40-30c0c40034bb" />

   b. Ajouter du contenu dans le fichier

<img width="567" height="56" alt="image" src="https://github.com/user-attachments/assets/121de941-ead3-47a2-b1f4-d97dd867b389" />

   c. Ajouter le fichier à l’index (staging area)

<img width="566" height="68" alt="image" src="https://github.com/user-attachments/assets/cbf87427-3d2d-4d90-ad92-0b655c227912" />

   d. Valider votre premier commit

<img width="549" height="87" alt="image" src="https://github.com/user-attachments/assets/cad2af27-f485-4a30-a54e-077bf82ec471" />

2. Historique des commits
   a. Afficher l’historique

<img width="572" height="290" alt="image" src="https://github.com/user-attachments/assets/ce816cfa-f11c-4927-b253-7739f0b23dbb" />

   b. Afficher les différences entre deux commits

<img width="1200" height="692" alt="image" src="https://github.com/user-attachments/assets/96ebf0b8-0d64-476c-bca2-dd9a322ea2f1" />

3. Annuler les modifications locales d’un fichier avant l’indexation

   $git checkout -- eda.py

4. Visualiser les fichiers dans le staging area

<img width="447" height="118" alt="image" src="https://github.com/user-attachments/assets/a5037118-a296-4b14-9b12-6c257fcaf60b" />

##Partie 4 : Collaborer sur Git
1. Créer une nouvelle branche:

++Créer une nouvelle branche :

<img width="491" height="46" alt="image" src="https://github.com/user-attachments/assets/ac5357dc-6a90-4d61-9200-ac008a060fec" />

++Basculer sur cette branche :

<img width="413" height="58" alt="image" src="https://github.com/user-attachments/assets/5eb96ba5-cf35-4fa6-a6e0-dd2e0d624192" />

2. Modifier, ajouter, committer et pousser les changements

<img width="557" height="324" alt="image" src="https://github.com/user-attachments/assets/580396aa-01e3-4a39-b058-19bf5fe00023" />

3. Gestion des conflits

<img width="553" height="587" alt="image" src="https://github.com/user-attachments/assets/fa31fa15-0dac-42bf-8121-469c194bc213" />

4. Suivre un dépôt distant et récupérer toutes les branches

<img width="484" height="158" alt="image" src="https://github.com/user-attachments/assets/068924ec-bf32-49df-aee6-ee6b74f184c6" />

5. Supprimer une branche locale après fusion

<img width="394" height="59" alt="image" src="https://github.com/user-attachments/assets/42f4cfa2-4503-4c6b-a9ab-21cef61fe01f" />

##Partie 5 : Rebase d'une branche sur ‘master’:

<img width="550" height="748" alt="image" src="https://github.com/user-attachments/assets/a906faa2-6ab8-445a-82dd-65543636404a" />

8. Interrompre un rebase en cours

++Si vous avez commis une erreur pendant le rebase (ou souhaitez tout annuler) :

$git rebase --abort

👉 Cela arrête le rebase et remet le dépôt dans l’état d’avant la commande git rebase.

9. Lister les commits qui vont être rebasés avant de lancer un rebase

++Avant d’exécuter le rebase, vous pouvez voir quels commits seront concernés :

$git log main..experiment-eda

👉 Cela affiche tous les commits qui existent dans experiment-eda mais pas dans master, c’est-à-dire ceux qui seront rejoués pendant le rebase.















   
   
   

   
   







