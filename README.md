# 📱 Android Data Transfer App
> **Exercice Académique** : Gestion de formulaires et navigation entre activités (Intents).

Ce projet est une application Android native illustrant la gestion des formulaires, l'interaction utilisateur et le passage de données entre deux écrans.

---

## 📝 Description de l'exercice
L'objectif est de créer une interface de saisie d'informations personnelles et d'afficher ces données sur un second écran après validation.

### 🌟 Fonctionnalités principales :
* **Écran 1 (Saisie) :** Formulaire complet avec `EditText` (Nom, Email, Téléphone, Adresse) et un `Spinner` pour la sélection de la **Ville**.
* **Validation & Envoi :** Récupération des données lors du clic sur le bouton **"Envoyer"**.
* **Écran 2 (Affichage) :** Réception des données via l'objet `Intent` et affichage récapitulatif.

---

## 🎥 Démonstration Vidéo
*Le lecteur ci-dessous présente le fonctionnement complet de l'application, de la saisie à l'affichage final.*

<div align="center">
  <video src="https://github.com/user-attachments/assets/7daf6c98-6bc4-4703-9f7f-502f9a006bc6" width="320" controls>
    Votre navigateur ne supporte pas la lecture de vidéos HTML5.
  </video>
</div>

---

## 🛠️ Détails Techniques
* **Langage :** Java / Kotlin (Android SDK)
* **Interface :** XML Layouts (`RelativeLayout` / `LinearLayout`)
* **Logique de navigation :** * `Intent.putExtra()` pour envoyer les données.
    * `getIntent().getStringExtra()` pour récupérer les informations.

---

## 🚀 Installation & Test
1. **Cloner le projet** :
   ```bash
   git clone [https://github.com/votre-utilisateur/votre-depot.git](https://github.com/votre-utilisateur/votre-depot.git)
