# 📱 Projet 7 : Coachly — Application Mobile Android

**Coachly** est une application mobile Android développée avec **React Native (Expo)**, connectée à un backend **PHP** hébergé sur un serveur **Apache**.  
Elle est actuellement en **test fermé sur le Google Play Store**.

---

## 🧠 Objectif

Coachly est une application dédiée à l'accompagnement psychologique, permettant de :

- Passer des **tests psychologiques** (auto-administrés ou proposés par un praticien)
- Obtenir un **résumé personnalisé généré par IA** avec des recommandations
- Consulter une IA intégrée nommée **Dr IA**
- Accéder à un **répertoire de praticiens** inscrits
- Offrir des **formules de paiement variées**, adaptées aux particuliers comme aux entreprises

---

## 🚀 Fonctionnalités principales

### ✅ Tests psychologiques
- Réalisables par l'utilisateur lui-même ou à la demande d’un **praticien**
- Résumé généré par IA avec **recommandations personnalisées**

### 🤖 Dr IA (IA conversationnelle)
- L'utilisateur peut se **confier à l'IA**
- **Suggestions de tests** adaptés selon les échanges

### 🧑‍⚕️ Espace Praticien
- Informations sur les **cabinets et praticiens partenaires**
- Interface dédiée pour gérer les recommandations et suivis

### 💳 Achats In-App
- **Formule personnelle** : achat de tests à l’unité ou par abonnement
- **Formule entreprise** : accès illimité pour tous les employés d'une entreprise via un **code entreprise**

---

## 🧪 État actuel

- 📦 Backend : PHP sur serveur Apache
- 📱 Frontend : React Native avec Expo
- 📲 Distribution : En **test fermé** sur le Google Play Store

---

## 🛠️ Technologies utilisées

- **Frontend :** React Native (Expo)
- **Backend :** PHP
- **Serveur :** Apache
- **Base de données :** MySQL
- **Paiement :** In-App Purchases (Google Play)
- **IA :** Intégration d’un système IA pour analyse et recommandations (via API OpenAI)

---

## 🧩 Architecture simplifiée

```txt
React Native (Expo)
        ↓
   API REST (PHP)
        ↓
   Base de données (MySQL)

````

## 🔐 Accès entreprise

  - Lors de l’inscription, un champ permet de saisir un code entreprise

  - Ce code débloque un accès illimité aux tests pour tous les employés concernés




