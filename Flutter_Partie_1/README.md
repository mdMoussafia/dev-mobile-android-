# Application Flutter Quiz et Météo
Cette application mobile Flutter combine deux fonctionnalités principales :

Une application de quiz interactive simple pour l'engagement utilisateur
Une application météo qui récupère des données météorologiques en temps réel via l'API OpenWeather

## Structure du projet
```
lib/
    ├── main.dart
    ├── answer.dart
    ├── question.dart
    ├── quiz.dart
    ├── score.dart
    ├── weather.dart
```

## Fonctionnalités
### Module Quiz :

Questions multiples avec choix de réponses
Suivi dynamique des scores
Retour sur les réponses sélectionnées

### Module Météo :

Utilise l'API OpenWeatherMap pour récupérer la météo actuelle
Affiche la température, description et données spécifiques à la ville
Clé API chargée de manière sécurisée depuis le fichier .env

## Variables d'environnement
Créer un fichier .env à la racine avec le format suivant :
```
OPENWEATHER_API_KEY=votre_cle_api_ici
```
## Dépendances

- flutter_dotenv
- http

### Installation avec :
```
flutter pub get
```

### Exécution de l'application
```
flutter run
```