---
description: Étapes détaillées pour déployer le site FredCare sur GitHub Pages
---

# Guide de Déploiement GitHub Pages

Suivez ces étapes pour mettre votre site en ligne.

## 1. Créer le dépôt sur GitHub
1. Connectez-vous à [GitHub](https://github.com).
2. Cliquez sur le bouton **"+"** en haut à droite et choisissez **"New repository"**.
3. Nommez-le `fredcare-cameroun` (ou le nom que vous préférez).
4. Laissez-le en **Public**.
5. Ne cochez **aucune** case (README, gitignore, etc.).
6. Cliquez sur **"Create repository"**.

## 2. Lier votre projet local à GitHub
Ouvrez votre terminal et exécutez ces commandes (remplacez `[URL_DU_REPO]` par l'URL que GitHub vous donnera) :

```bash
git remote add origin [URL_DU_REPO]
git branch -M main
git push -u origin main
```

## 3. Activer GitHub Pages
1. Sur la page de votre dépôt sur GitHub, allez dans l'onglet **Settings**.
2. Dans le menu de gauche, cliquez sur **Pages**.
3. Sous **Build and deployment**, vérifiez que la source est **"Deploy from a branch"**.
4. Sous **Branch**, sélectionnez `main` et le dossier `/(root)`.
5. Cliquez sur **Save**.

Votre site sera en ligne dans quelques minutes ! l'URL apparaîtra en haut de la page Settings > Pages.
