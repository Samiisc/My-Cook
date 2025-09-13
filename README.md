# 🍲 Application de Recettes – Flutter & Dart

## 📖 Description
Cette application mobile multiplateforme (**Android & iOS**) permet aux utilisateurs de :
- Parcourir une liste de recettes.
- Consulter les détails d’une recette (ingrédients, étapes, temps de cuisson).
- Sauvegarder leurs recettes préférées.
- Rechercher et filtrer par nom, catégorie ou type de repas.

Ce projet est pensé comme **support pédagogique** pour apprendre Flutter & Dart :
- Manipulation de données complexes.
- Navigation multi-pages.
- Gestion d’état.
- UI responsive et moderne.

---

## 🎯 Objectifs pédagogiques
- Manipuler des **listes et modèles de données** (recettes, ingrédients, étapes).
- Créer une **navigation avancée** avec onglets (Tabs), menu latéral (Drawer), et éventuellement une Bottom Navigation Bar.
- Construire une **interface responsive** avec images, boutons et textes.
- Implémenter une **gestion d’état** (Provider ou setState pour débuter).
- Gérer des **assets** (images locales et en ligne).

---

## 🔑 Fonctionnalités
- 📋 **Liste des recettes** avec images, titres et courtes descriptions.  
- 🍳 **Détails d’une recette** : ingrédients, préparation, temps de cuisson.  
- ⭐ **Favoris** : ajouter ou retirer une recette.  
- 🔍 **Recherche & filtres** (nom, catégorie, type de repas).  
- 🧭 **Navigation intuitive** :
  - Tabs (onglets).
  - Drawer (menu latéral).
  - Bottom navigation bar (optionnel).  
- 📱 **UI responsive** adaptée aux mobiles.

---

## 🛠️ Technologies utilisées
- **Langage** : Dart  
- **Framework** : Flutter  
- **IDE conseillés** : Android Studio, VS Code  
- **Gestion d’état** : Provider (ou `setState` pour débuter)  
- **Assets** : images locales (`assets/`) + images réseau  

---

## 📂 Structure du projet

lib/
│── main.dart # Point d'entrée
│
├── models/ # Modèles de données
│ └── recipe.dart
│
├── pages/ # Écrans principaux
│ ├── home_page.dart
│ ├── recipe_detail_page.dart
│ └── favorites_page.dart
│
└── widgets/ # Widgets réutilisables
└── recipe_card.dart


---

## 🚀 Améliorations futures
- 🔔 Notifications push (nouvelle recette du jour).  
- 🌐 Synchronisation avec une base de données (Firebase, Supabase).  
- 👤 Gestion des utilisateurs (connexion/inscription).  
- 📤 Partage de recettes entre utilisateurs.  

---

## ▶️ Installation & Exécution
1. **Cloner le projet**  
   ```bash
   git clone https://github.com/ton-compte/app-recettes.git
   cd app-recettes
