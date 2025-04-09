# fichiers-prénoms

## Cloner le projet
Par commande:
git clone https://github.com/Poluux/fichiers-prenoms.git
cd fichier-prenoms

## Créer chacun une branche
Par commande:
git checkout -b ajout-prenom-"prenom"

## Récupérer les branches de tout le monde
Par VS Code:
![image](https://github.com/user-attachments/assets/99794927-efc6-464e-a280-7cd149e95ace)

Par commande :
git fetch origin

## Check différence Origin / Local
Maintenant que fetch est fait, aller sur la branche Hugo
![image](https://github.com/user-attachments/assets/2eb978c5-b46f-4891-b9e6-bf77ccd20fc8)
![image](https://github.com/user-attachments/assets/eb75a200-dce7-4e11-981f-a905935c6671)


Ouvrez prenoms.txt --> devrait être vide (si je me trompe pas)
Vide car vous avez récupérer le lien avec Origin (github)

pull la branche Hugo pour voir les modifications

Par VS Code:
![image](https://github.com/user-attachments/assets/a66a8f29-1c7c-40dc-82bb-78b26e666b6d)

Par commande:
git pull

Vous devriez voir prenoms.txt s'update --> Votre branche en Local est à jour

## Commit et push modifications
Revenez sur votre branche
Ajouter votre nom dans prenoms.txt

Par VS Code:
appuyer sur le + pour stage les fichiers avant de commit
![image](https://github.com/user-attachments/assets/5f007ac7-e7cc-4d9d-a0e4-5b044762b8c6)
![image](https://github.com/user-attachments/assets/3dca7828-cc4a-4c2e-8fd9-cb9bc4a4a8a1)

Par commande:
git add prenoms.txt
git commit -m "Ajout du prénom Hugo"
git push origin ajout-prenom-Hugo

Origin(github) est maintenant à jour !

## Créez une pull request pour fusionner deux branches

!!! Important mais on en redisctuera !!!
faire un git pull de la branche dans laquelle vous voulez fusionner votre travail.

Par VSCode:
![image](https://github.com/user-attachments/assets/4f3d2578-72ce-47e9-8e27-58bf53d69e1d)

Ou rebase
![image](https://github.com/user-attachments/assets/340f4048-b6c1-43c7-bef9-b2dd7ad790bb)

Par commande:
git pull origin main

ce que ça fait, récupère ce qu'il y a dans main si d'autres ont travaillé dessus avant d'ajouter les modifs de votre branche.

!!! Fin du important !!!
----------------------------------------------------------------------------------------

Ouvrez github:
![image](https://github.com/user-attachments/assets/7b8f5622-c92b-4760-a7b6-efe39c0e165b)

cliquer sur new
![image](https://github.com/user-attachments/assets/5528285f-2ec3-446a-b279-27022c0fc54f)

votre branche à droite, celle dans laquelle vous voulez mettre vos données sur la gauche puis create pull request
![image](https://github.com/user-attachments/assets/ca9d3723-6160-4f8a-822c-9e0f008f5b88)
![image](https://github.com/user-attachments/assets/4be346a5-7f62-40a4-8b1b-3d9847db2378)

vous pouvez aller sur main et pull pour voir que votre nom a été ajouté





