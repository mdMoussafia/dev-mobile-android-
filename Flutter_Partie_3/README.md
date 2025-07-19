# Application Tic Tac Toe Auth App – IIBDCC Mobile UI Showcase
Une application mobile Flutter simple mais instructive pour le cursus BDCC. Ce projet a commencé comme une démonstration de navigation et d'animation de base, et a évolué vers un jeu de Tic Tac Toe protégé par une connexion.
## Fonctionnalités ajoutées

- Écrans de connexion et d'inscription avec stockage local des identifiants utilisant SharedPreferences
- Connexion sauvegardée : L'utilisateur reste connecté entre les sessions
- Fonctionnalité de déconnexion depuis l'écran Tic Tac Toe
- Logique de jeu Tic Tac Toe : Détecte le gagnant ou l'égalité
- Dialogue de résultat popup : Affiche le gagnant ou "Égalité"

## Commencer

Cloner le dépôt
```
git clone https://github.com/saadbr/flutter_nav_data.git
cd flutter_nav_data
```

## Installer les dépendances
```
flutter pub get
```
## Exécuter l'application
```
flutter run
```


Émulateur ou appareil réel avec Android SDK 34+ recommandé

## Structure des dossiers
```
lib/
├── main.dart
├── screen/
├──login.screen.dart
├── signup.screen.dart
└── tictactoe.screen.dart
```