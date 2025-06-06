# Job_App_for_Manage-Frontend


## 📝 Description

**Job_App_for_Manage-Frontend** est une application de gestion des clients et des ventes développée en **Vue.js**.  
Elle permet aux utilisateurs enregistrés d’ajouter, visualiser et exporter les ventes de manière intuitive.

L'application gère deux rôles :

- 👤 **Employé** : peut enregistrer les informations des clients (nom, contact, adresse, montant…)
- 👑 **Admin** : peut visualiser l’ensemble des ventes, générer des statistiques mensuelles et exporter les rapports en PDF.

---

## ⚙️ Fonctionnalités principales

### 🔐 Authentification

- Création de compte (un seul compte admin possible)
- Connexion / Déconnexion
- Session sauvegardée en `LocalStorage`

### 👤 Employé

- Enregistrement de clients avec les champs :
  - Nom, Prénom
  - Contact, Adresse
  - Article vendu, Montant, Date
- Données sauvegardées dans le navigateur (`localStorage`)

### 👑 Admin

- Affichage de toutes les ventes
- Filtres :
  - Par **année**
  - Par **mois**
- Visualisation des ventes par mois via un **graphique en barres**
- Export des ventes en **PDF** :
  - Total
  - Par employé spécifique

---

## 🛠️ Technologies utilisées

- [Vue.js 3 (Composition API + `<script setup>`)](https://vuejs.org/)
- [Pinia](https://pinia.vuejs.org/) (gestion de l’état)
- [Vue Router](https://router.vuejs.org/)
- [Chart.js](https://www.chartjs.org/) (graphique de ventes)
- [jsPDF + jspdf-autotable](https://github.com/parallax/jsPDF) (export PDF)
- [Animate.css](https://animate.style/) (animations visuelles)
- `LocalStorage` (pour persister les données)

---

## ▶️ Instructions pour exécuter l’application

1. **Cloner le projet** :

```bash
git clone https://github.com/ton-compte/job_app.git
cd job_app
