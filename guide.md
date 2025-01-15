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

### Remarques importantes
- Assurez-vous d'avoir Git installé sur votre machine. Vous pouvez vérifier avec :
```bash
git --version

   

## Ajouter des fichiers et gérer les versions.
## Pousser les modifications sur GitHub.

## Conclusion
Ce guide est destiné aux débutants souhaitant maîtriser Git et GitHub.
