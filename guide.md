# Guide Pratique

## Introduction
Ce document contient des instructions pratiques pour apprendre à utiliser Git et GitHub.

## Sections

  ## Créer un dépôt GitHub
Pour créer un dépôt sur GitHub :
1. Connectez-vous à votre compte GitHub.
2. Cliquez sur le bouton **New** ou allez dans **Repositories > New**.
3. Remplissez les informations :
   - Nom du dépôt (obligatoire).
   - Description (optionnelle).
   - Choisissez la visibilité (**Public** ou **Private**).
4. Cliquez sur **Create repository** pour valider.

## Cloner un dépôt

Cloner un dépôt permet de copier un projet hébergé sur GitHub (ou un autre service) vers votre machine locale pour y travailler. Voici les étapes à suivre :

### Étapes pour cloner un dépôt GitHub

1. **Accéder au dépôt GitHub** :  
   - Rendez-vous sur la page du dépôt que vous souhaitez cloner.

2. **Copier l'URL du dépôt** :  
   - Cliquez sur le bouton **Code** (généralement en haut à droite de la page du dépôt).
   - Sélectionnez l'option **HTTPS**, **SSH**, ou **GitHub CLI**, puis copiez l'URL affichée.

   Exemple d'URL HTTPS :
   
3. **Cloner le dépôt avec Git** :  
- Ouvrez un terminal ou un invite de commandes sur votre machine locale.
- Exécutez la commande suivante en remplaçant `<url-du-depot>` par l'URL copiée :
  ```bash
  git clone <url-du-depot>
  ```
- Par exemple :
  ```bash
  git clone https://github.com/votre-nom-utilisateur/guide-pratique.git
  ```

4. **Accéder au dossier cloné** :  
- Une fois le dépôt cloné, accédez au dossier en utilisant la commande :
  ```bash
  cd nom-du-dossier
  ```
- Exemple :
  ```bash
  cd guide-pratique
  ```

### Ajouter des fichiers et gerer les versions


Git permet de suivre les modifications apportées aux fichiers d’un projet et de maintenir un historique complet des versions. Voici comment ajouter des fichiers et gérer les versions avec Git.

### Étapes pour ajouter des fichiers et gérer les versions

1. **Ajouter un nouveau fichier ou modifier un fichier existant** :
   - Créez un fichier ou apportez des modifications à un fichier existant dans votre projet local.
   - Par exemple, ajoutez un fichier nommé `exemple.txt` :
     ```bash
     echo "Ceci est un exemple." > exemple.txt
     ```

2. **Suivre les modifications avec Git** :
   - Ajoutez le fichier ou les modifications à l'index (zone de staging) avec la commande :
     ```bash
     git add <nom-du-fichier>
     ```
     Exemple :
     ```bash
     git add exemple.txt
     ```
   - Pour ajouter tous les fichiers modifiés ou nouveaux, utilisez :
     ```bash
     git add .
     ```

3. **Valider les modifications** :
   - Validez les fichiers ajoutés à l’index avec un message décrivant les modifications :
     ```bash
     git commit -m "Ajout du fichier exemple.txt avec du contenu initial"
     ```

4. **Envoyer les modifications sur GitHub** :
   - Si vous souhaitez sauvegarder vos modifications sur GitHub (ou un autre dépôt distant), utilisez la commande :
     ```bash
     git push origin <nom-de-la-branche>
     ```
     Exemple pour une branche `main` :
     ```bash
     git push origin main
     ```

### Vérifier l’historique des versions
- Vous pouvez consulter l’historique des validations (commits) avec :
  ```bash
  git log


   

## Pousser les modifications sur GitHub.

## Conclusion
Ce guide est destiné aux débutants souhaitant maîtriser Git et GitHub.
