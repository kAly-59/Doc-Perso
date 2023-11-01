### GIT :

**Installation sur Linux :**
```
sudo apt install git
```

**Configuration de Git :**
```
git --version
git config --global user.name "Votre Nom"
git config --global user.email "votre@email.com"
```

1. **`git init` :**
   - *Fonctionnement :* Initialise un nouveau dépôt Git dans un répertoire existant.
   - *Utilité :* Utilisé pour commencer un nouveau projet Git. Le répertoire devient un dépôt Git, prêt à enregistrer les modifications.

2. **`git add` :**
   - *Fonctionnement :* Ajoute des modifications spécifiques (ou tous les fichiers modifiés) à la staging area (zone de préparation).
   - *Utilité :* Sélectionne les modifications à inclure dans le prochain commit. Peut ajouter des fichiers individuels (`git add nom_du_fichier`) ou tous les fichiers modifiés (`git add .`).

3. **`git status` :**
   - *Fonctionnement :* Affiche l'état des fichiers dans le répertoire de travail et de la staging area.
   - *Utilité :* Permet de voir les fichiers modifiés, ceux dans la staging area, et si tout est prêt pour le commit.

4. **`git commit` :**
   - *Fonctionnement :* Crée un nouveau commit avec les modifications de la staging area.
   - *Utilité :* Enregistre les modifications dans l'historique du projet. Un message de commit (`-m "Message du commit"`) décrit les changements effectués.

5. **`git pull` :**
   - *Fonctionnement :* Récupère les modifications depuis un dépôt distant et les fusionne dans votre branche actuelle.
   - *Utilité :* Met à jour votre copie locale avec les dernières modifications du dépôt distant.

6. **`git push` :**
   - *Fonctionnement :* Envoie les commits locaux vers un dépôt distant.
   - *Utilité :* Partage vos modifications avec les collaborateurs en poussant les commits vers le dépôt distant.

7. **`git clone` :**
   - *Fonctionnement :* Crée une copie locale d'un dépôt distant existant.
   - *Utilité :* Permet de créer une copie de travail d'un projet distant sur votre machine pour contribuer au projet.

8. **`git remote` :**
   - *Fonctionnement :* Gère les dépôts distants associés à votre projet local.
   - *Utilité :* Permet d'ajouter, afficher ou supprimer des dépôts distants. Vous pouvez également renommer ou mettre à jour les URL des dépôts distants avec cette commande.