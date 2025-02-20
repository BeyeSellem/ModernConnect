# 📱 Réseau Social Moderne

🚀 Une plateforme de réseau social de nouvelle génération conçue pour des interactions fluides, une expérience utilisateur optimisée et une navigation intuitive.

---

## 📋 Table des matières

- 🤖 Introduction
- ⚙️ Technologies utilisées
- 🔋 Fonctionnalités
- 🤸 Démarrage rapide
- 🛠️ Configuration de l'environnement
- 🔗 Liens & Ressources

---

## 🤖 Introduction

Cette application de réseau social permet aux utilisateurs de créer, explorer et interagir facilement avec du contenu. Développée avec des technologies modernes, elle offre une interface fluide et une expérience utilisateur optimisée.

### Pourquoi ce projet ?

- Une plateforme intuitive et moderne pour partager du contenu.
- Des fonctionnalités interactives comme les likes, les favoris et la gestion de profil.
- Une architecture performante et évolutive avec des mises à jour dynamiques et un scroll infini.
- Optimisation avancée du cache et des performances pour un chargement rapide des données.

---

## ⚙️ Technologies utilisées

Ce projet est construit avec les technologies suivantes :

- **React.js** – Bibliothèque JavaScript pour construire des interfaces utilisateurs dynamiques.
- **Appwrite** – Backend as a Service (BaaS) pour l'authentification, la base de données et le stockage.
- **React Query (Tanstack Query)** – Gestion optimisée du fetching, du cache et de la synchronisation des données.
- **Tailwind CSS** – Système de styles moderne basé sur les classes utilitaires.
- **ShadCN** – Composants UI pour une expérience fluide et esthétique.
- **TypeScript** – Sécurité et maintenabilité du code.

---

## 🔋 Fonctionnalités

👉 **Authentification utilisateur** – Système sécurisé de connexion et gestion des comptes.

👉 **Flux d'exploration** – Découverte des publications tendances et des créateurs populaires.

👉 **Création de publications** – Ajout de contenus sous forme d’images et de textes.

👉 **Likes & favoris** – Interaction avec les publications en les likant et les sauvegardant.

👉 **Gestion de profil** – Personnalisation et mise à jour des profils utilisateurs.

👉 **Scroll infini** – Chargement dynamique des publications pour une expérience utilisateur fluide.

👉 **Mises à jour en temps réel** – Récupération rapide des données grâce à React Query.

👉 **Optimisation du cache** – Réduction des requêtes inutiles en stockant localement les données fréquemment utilisées.

👉 **Requêtes parallèles et pré-fetching** – Chargement intelligent des données pour améliorer la réactivité de l'application.

👉 **Synchronisation automatique** – Mise à jour des données en arrière-plan pour garantir un contenu toujours actualisé.

👉 **Interface responsive** – Design optimisé pour mobile et desktop avec Tailwind CSS & ShadCN.

👉 **Backend avec Appwrite** – Gestion complète de l’authentification, des bases de données et du stockage.

---

## 🤸 Démarrage rapide

Suivez ces étapes pour configurer le projet localement.

### Prérequis

Assurez-vous d'avoir installé :

- **Git**
- **Node.js** (version LTS recommandée)
- **npm** ou **yarn**

### Clonage du dépôt

```bash
git clone https://github.com/your-username/social-media-app.git
cd social-media-app
```

### Installation des dépendances

```bash
npm install   # ou yarn install
```

### Lancement du projet

```bash
npm run dev   # ou yarn dev
```

Ouvrez [http://localhost:3000](http://localhost:3000) dans votre navigateur pour voir l'application.

---

## 🛠️ Configuration de l'environnement

Créez un fichier `.env.local` à la racine du projet et ajoutez les variables suivantes :

```env
VITE_APPWRITE_URL=
VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_STORAGE_ID=
VITE_APPWRITE_USER_COLLECTION_ID=
VITE_APPWRITE_POST_COLLECTION_ID=
VITE_APPWRITE_SAVES_COLLECTION_ID=
```

Remplacez les valeurs par vos informations Appwrite.

---

## 🔗 Liens & Ressources

- 📖 [Documentation React](https://react.dev/)
- 🔧 [Documentation Appwrite](https://appwrite.io/docs)
- 🎨 [Documentation Tailwind CSS](https://tailwindcss.com/docs)
- 🖥️ [Composants ShadCN](https://ui.shadcn.com/)
- ⚡ [React Query](https://tanstack.com/query/latest/docs/react/overview)

---

🚀 Lancez votre propre réseau social dès aujourd'hui !
