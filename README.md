# MaliTrek Prestige - Expéditions de Luxe au Mali

MaliTrek Prestige est une plateforme de réservation et de suivi d'expéditions de trekking haut de gamme au Mali.

## 🚀 Déploiement sur Firebase Hosting

Pour déployer cette application sur votre propre projet Firebase, suivez ces étapes :

### 1. Prérequis
- Un compte Firebase.
- Node.js installé (LTS recommandé).
- Firebase CLI installé (`npm install -g firebase-tools`).

### 2. Initialisation
Dans le répertoire racine du projet :
```bash
# Se connecter à Firebase
firebase login

# Initialiser le projet (si ce n'est pas déjà fait)
# Sélectionnez Hosting et choisissez votre projet Firebase existant
firebase init hosting
```
*Note: Lors de l'initialisation, assurez-vous de choisir `dist` comme dossier public et répondez `Yes` à la question "Configure as a single-page app".*

### 3. Build & Déploiement
```bash
# Installer les dépendances
npm install

# Construire l'application
npm run build

# Déployer sur Firebase
firebase deploy
```

## 📱 Installation PWA (Mode Application)
L'application est configurée comme une **Progressive Web App (PWA)**. 
- Sur **iPhone/Safari** : Appuyez sur le bouton "Partager" et choisissez "Sur l'écran d'accueil".
- Sur **Android/Chrome** : Appuyez sur les trois points (menu) et choisissez "Installer l'application".

## 🛠 Variables d'environnement
Créez un fichier `.env` basé sur `.env.example` pour configurer vos clés API Gemini si nécessaire.

## 🎨 Personnalisation des icônes
Remplacez les fichiers suivants dans le dossier `public/` par vos propres logos pour personnaliser l'icône de l'application :
- `favicon.png` (32x32)
- `icon-192.png` (192x192)
- `icon-512.png` (512x512)
