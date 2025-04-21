# 🏠 Application Web de publication et de recherche d’annonces immobilières

Ce projet a été réalisé dans le cadre du module **IGL (Ingénierie du Logiciel)** à l’**École Nationale Supérieure d’Informatique (ESI)**.  
L’objectif est de concevoir une **application web responsive** permettant à des utilisateurs de **publier, consulter et filtrer des annonces immobilières (AI)**, ainsi que de les enrichir à l’aide d’un administrateur via **web scraping** ou **flux RSS**.

---

## 🎯 Fonctionnalités principales

### 👤 Utilisateurs

- Déposer une annonce (vente, location, échange, vacances)
- Rechercher des biens par mots-clés dans le titre ou la description
- Filtrer les résultats selon :
  - Type du bien
  - Wilaya / commune
  - Période de publication
- Visualiser les annonces avec :
  - Galerie d’images
  - Localisation sur Google Maps
- Sauvegarder des annonces comme favorites
- Envoyer un message à un annonceur
- Gérer ses propres annonces et consulter les offres reçues

### 🧑‍💼 Administrateur

- Authentification sécurisée via **Google SSO**
- Récupération automatique d’annonces depuis d’autres sites via :
  - Web Scraping
  - Flux RSS

---

## 🛠️ Technologies utilisées

| Composant | Technologie |
|----------|-------------|
| **Backend** | [FastAPI](https://fastapi.tiangolo.com/) + [Uvicorn](https://www.uvicorn.org/) |
| **Frontend** | [React.js](https://reactjs.org/) |
| **Base de données** | SGBD relationnel (ex : PostgreSQL, MySQL) |
| **Authentification** | Google OAuth 2.0 (SSO) |
| **Web Scraping** | Python + BeautifulSoup |
| **Tests** | 3 tests unitaires + 1 test fonctionnel (Selenium) |
| **Modélisation** | Software Ideas Modeler |
| **Éditeur** | Visual Studio Code|
| **Environnement Python** | Anaconda |


---

## 🧪 Qualité et bonnes pratiques

- 🔐 Aucune clé secrète n’est présente dans le code : les identifiants sont stockés via **variables d’environnement**
- ✅ Tests automatisés (unitaires et fonctionnels)
- 💡 Documentation générée automatiquement via FastAPI
- 📱 Interface responsive adaptée aux mobiles et tablettes

---

