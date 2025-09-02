📖 Cahier des charges – Application de Recettes 🍲
🎯 Objectifs du projet

Développer une application mobile multiplateforme (Android & iOS) avec Flutter & Dart permettant aux utilisateurs de parcourir, consulter et sauvegarder leurs recettes préférées.

Cette application servira de projet pédagogique pour apprendre à manipuler des données complexes, mettre en place une navigation avancée et gérer l’état dans Flutter.

🔑 Fonctionnalités principales

📋 Liste des recettes : affichage avec images, titres et courtes descriptions.

🍳 Détails d’une recette : ingrédients, étapes de préparation, temps de cuisson.

⭐ Sauvegarde des favoris : possibilité d’ajouter/enlever une recette des favoris.

🔍 Recherche & filtres : par nom, catégorie ou type de repas (petit-déjeuner, déjeuner, végétarien, etc.).

🧭 Navigation intuitive :

Tabs (onglets)

Drawer (menu latéral)

Bottom navigation bar (optionnel)

📱 UI responsive : interface adaptée aux mobiles.

🛠️ Technologies utilisées

Langage : Dart

Framework : Flutter

IDE conseillé : Android Studio ou VS Code

Gestion d’état : Provider (ou setState pour débuter)

Gestion des assets : images locales (dans assets/) + images réseau

📂 Structure du projet (proposée)
lib/
│── main.dart                # Point d'entrée
│
├── models/                  # Modèles de données
│   └── recipe.dart
│
├── pages/                   # Écrans principaux
│   ├── home_page.dart
│   ├── recipe_detail_page.dart
│   └── favorites_page.dart
│
└── widgets/                 # Widgets réutilisables
    └── recipe_card.dart


📚 Objectifs pédagogiques (pour étudiants)

Manipuler des listes et données complexes (recettes, ingrédients, étapes).

Créer une navigation multi-pages avec onglets et menus latéraux.

Construire une interface claire et responsive (texte, images, boutons).

Mettre en œuvre une gestion d’état pour gérer les favoris.

🚀 Améliorations futures

🔔 Notifications push (nouvelle recette du jour).

🌐 Synchronisation avec une base de données (Firebase, Supabase).

👤 Gestion d’utilisateurs (connexion/inscription).

📤 Partage de recettes entre utilisateurs.
