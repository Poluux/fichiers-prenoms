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
Stage the files you want to push
![image](https://github.com/user-attachments/assets/5f007ac7-e7cc-4d9d-a0e4-5b044762b8c6)
![image](https://github.com/user-attachments/assets/3dca7828-cc4a-4c2e-8fd9-cb9bc4a4a8a1)



