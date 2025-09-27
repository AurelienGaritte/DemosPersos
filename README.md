# 🛒 ProductStore - Application MERN Stack

Une application web moderne de gestion de produits développée avec la stack MERN (MongoDB, Express.js, React, Node.js).

## 📋 Table des matières

- [Rendu visuel](#-rendu-visuel)
- [Technologies utilisées](#-technologies-utilisées)
- [Architecture du projet](#-architecture-du-projet)
- [Installation](#-installation)
- [Utilisation](#-utilisation)
- [Fonctionnalités](#-fonctionnalités)

## 📹 Rendu visuel

### **🛣️ Routes fonctionnelles // 🌇 Thème Dark/Light**

![Démonstration des routes et du thème](./assets/RoutesFonctionnelles.gif)

### **📱 Responsive Ready**

![Démonstration responsive](./assets/Responsive.gif)

### **➕ Ajout de produit**

![Démonstration de l'ajout de produit](./assets/Ajout.gif)

### **✏️ Modification de produit**

![Démonstration de la modification de produit](./assets/Modification.gif)

### **❌ Suppression**

![!Démonstration de la suppression](./assets/Suppression.gif)

## 🚀 Technologies utilisées

### **Backend (Node.js)**

#### **Frameworks et Bibliothèques principales**

- **Express.js** `^5.1.0` - Framework web minimaliste et flexible pour Node.js

  - Gestion des routes API REST
  - Middleware pour le parsing JSON
  - Serveur HTTP intégré

- **Mongoose** `^8.18.2` - ODM (Object Document Mapper) pour MongoDB
  - Modélisation des données avec des schémas
  - Validation des données automatique
  - Requêtes simplifiées vers MongoDB

#### **Utilitaires et Configuration**

- **dotenv** `^17.2.2` - Gestionnaire de variables d'environnement

  - Chargement sécurisé des configurations (.env)
  - Séparation des configurations par environnement

- **cross-env** `^10.0.0` - Configuration des variables d'environnement cross-platform
  - Compatible Windows, macOS, Linux
  - Définition de NODE_ENV de manière universelle

#### **Outils de développement**

- **nodemon** `^3.1.10` - Redémarrage automatique du serveur
  - Surveillance des changements de fichiers
  - Rechargement à chaud en développement

### **Frontend (React)**

#### **Framework principal**

- **React** `^19.1.1` - Bibliothèque JavaScript pour les interfaces utilisateur

  - Composants fonctionnels avec Hooks
  - Gestion d'état local et global
  - Virtual DOM pour des performances optimales

- **React DOM** `^19.1.1` - Rendu des composants React dans le DOM
  - Hydratation SSR
  - Portals pour le rendu hors hiérarchie

#### **Routage**

- **React Router DOM** `^7.9.2` - Navigation côté client
  - Routage déclaratif
  - Navigation programmable
  - Gestion de l'historique du navigateur

#### **Interface utilisateur**

- **Chakra UI** `^2.10.9` - Bibliothèque de composants UI modulaires

  - Système de design cohérent
  - Thème sombre/clair intégré
  - Composants accessibles (ARIA)
  - Responsive design

- **Chakra UI Icons** `^2.2.4` - Collection d'icônes pour Chakra UI

  - Icônes vectorielles optimisées
  - Intégration parfaite avec Chakra UI

- **React Icons** `^5.5.0` - Bibliothèque d'icônes populaires
  - Icônes de Font Awesome, Feather, Material Design
  - Composants React prêts à l'emploi

#### **Animations**

- **Framer Motion** `^12.23.21` - Bibliothèque d'animations pour React
  - Animations fluides et performantes
  - Transitions de page
  - Animations gestuelles

#### **Gestion d'état**

- **Zustand** `^5.0.8` - Gestionnaire d'état léger et simple
  - Store global minimal
  - API simple et intuitive
  - TypeScript friendly

### **Outils de développement Frontend**

#### **Build Tools**

- **Vite** `^7.1.7` - Outil de build ultra-rapide

  - Hot Module Replacement (HMR) instantané
  - Build optimisé pour la production
  - Support ES modules natif

#### **Linting et qualité de code**

- **ESLint** `^9.36.0` - Linter JavaScript/TypeScript

  - Détection des erreurs de code
  - Application des bonnes pratiques
  - Formatage automatique

### **Base de données**

- **MongoDB** - Base de données NoSQL orientée documents
  - Stockage flexible des données JSON
  - Scalabilité horizontale
  - Requêtes puissantes et indexation

## ✨ Fonctionnalités

- ✅ **CRUD complet** - Créer, lire, mettre à jour, supprimer des produits
- ✅ **Interface responsive** - Design adaptatif mobile/desktop
- ✅ **Thème sombre/clair** - Basculement automatique
- ✅ **Gestion d'état globale** - Store Zustand pour les produits
- ✅ **API REST** - Endpoints structurés et sécurisés
- ✅ **Validation des données** - Côté client et serveur
- ✅ **Animations fluides** - Transitions avec Framer Motion
- ✅ **Hot Reload** - Développement avec rechargement instantané

## 🎯 Points techniques

### **Pourquoi cette stack ?**

**MERN Stack** = **Cohérence JavaScript** sur toute la pile technologique

- **MongoDB** : Flexibilité NoSQL pour le prototypage rapide
- **Express.js** : Simplicité et performance pour les APIs
- **React** : Écosystème riche et communauté active
- **Node.js** : Runtime JavaScript côté serveur

**Chakra UI** = **Productivité maximale**

- Composants pré-stylés et accessibles
- Système de thème intégré
- Documentation excellente

**Zustand** = **Gestion d'état simple**

- API intuitive
- Performance optimale

**Vite** = **Expérience développeur optimale**

- Build instantané
- HMR ultra-rapide
- Configuration minimale

---

## 👨‍💻 Auteur

Développé avec ❤️ par **Aurélien**

## 📝 License

Ce projet est sous licence ISC.
