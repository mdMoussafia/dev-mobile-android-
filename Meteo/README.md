# Meteo App – Android Weather Forecast

Meteo est une application Android affichant les prévisions météo par intervalles de 3 heures via l'API OpenWeatherMap. Développée avec Jetpack Compose pour smartphones et montres Wear OS.

## Features

-  Recherche de Ville : Saisissez une ville pour les prévisions en temps réel
-  Détails Météo : Date/heure, températures min/max, pression, humidité, icônes dynamiques
-  Interface Material 3 : Thèmes sombres et clairs personnalisés
-  Support Wear OS : Version optimisée pour écrans circulaires

##  Tech Stack

- Kotlin – Langage principal
- Jetpack Compose – Interface déclarative
- Material 3 – Composants Material Design
- ViewModel – Gestion des données
- Coroutines – Appels API asynchrones

---

## API Key

Insérez votre clé API dans WeatherViewModel.kt :
```kotlin
private val apiKey = "YOUR_API_KEY_HERE"
```
Obtenez votre clé: https://openweathermap.org/api

## 🧪 Requirements
- Min SDK: 26 (required for Wear Compose)
- Target SDK: 34
- Kotlin: 1.9.23+
- Compose Compiler: Compatible version based on Kotlin

