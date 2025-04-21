# 🏠 Application Web de publication et de recherche d’annonces immobilières

Ce projet a été réalisé dans le cadre du module **IGL (Ingénierie du Logiciel)** à l’**École Nationale Supérieure d’Informatique (ESI)**.  
Il a pour objectif de concevoir et implémenter une **application Web complète** permettant la publication, la consultation et la recherche d’annonces immobilières (AI).

---

## 🎯 Objectifs principaux

L’application permet à un utilisateur authentifié de :

- 📝 Publier des annonces immobilières (vente, location, échange, vacances)
- 🔍 Rechercher des biens par mots-clés dans le titre et la description
- 🧰 Filtrer les résultats selon :
  - Le type de bien
  - La Wilaya
  - La commune
  - Une période de publication
- 🖼️ Voir les détails d’une annonce (photos + localisation sur Google Maps)
- ⭐ Sauvegarder des annonces favorites
- ✉️ Envoyer un message à l’annonceur
- 📋 Gérer ses propres annonces et consulter les offres reçues

---

## 🧑‍💼 Fonctionnalités administrateur

- 🔐 Authentification via un **compte Google (SSO)**
- 🤖 Récupération automatisée d’annonces depuis d’autres sites via :
  - **Web scraping**
  - **Flux RSS**

---

## 🛠️ Technologies utilisées

- 🐍 **Backend** : Python
- ⚛️ **Frontend** : React
- 🗄️ **Base de données** : SGBD relationnel (ex : PostgreSQL, MySQL)
- 🔐 **Authentification** : Google SSO
- 🧪 **Tests** :
  - 3 tests unitaires
  - 1 test fonctionnel automatisé (ex : avec Selenium)
- 🚀 **Déploiement & gestion de version** : GitHub

