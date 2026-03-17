<div align="center">

# ⚡ NetPulse

**Speedtest moderne 100% français — fichier HTML unique, zéro dépendance**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/fr/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-4361ee?style=flat-square)](LICENSE)

<br/>

![NetPulse Preview](https://placehold.co/900x480/eef1ff/4361ee?text=NetPulse+v1.0&font=outfit)

</div>

---

## 📖 À propos

**NetPulse** est une interface de test de vitesse internet moderne, entièrement développée en HTML/CSS/JS vanilla. Pas de framework, pas de build, pas de serveur. Un seul fichier `.html` à ouvrir dans votre navigateur.

L'interface propose un design épuré en thème clair, une typographie soignée (**Outfit** + **Space Mono**) et une navigation fluide en onglets.

---

## ✨ Fonctionnalités

### 🚀 Test de vitesse
- Jauge animée en temps réel (0 → 1000 Mbps)
- Mesure de la **latence (ping)**, du **débit descendant** et du **débit montant**
- Barre de progression par phase avec pourcentage
- Calcul du **score réseau global** (/100)
- Statistiques avancées : gigue (jitter), perte de paquets, protocole

### 📶 Sélection de serveur
- Bouton **"Meilleur serveur"** — détecte et sélectionne automatiquement le serveur le plus rapide
- Rotation manuelle entre 5 serveurs FR/EU
- Badge de latence affiché en temps réel

### 🏆 Top Opérateurs
- Classement des 6 opérateurs français (Orange, Free, SFR, Bouygues…)
- Tri par **débit**, **couverture** ou **latence**
- Barres de progression animées + pills 5G / 4G / 3G
- Graphique comparatif (Chart.js)

### 🗺️ Carte des antennes
- Carte de France vectorielle avec **31 antennes** réparties sur les vraies villes
- Points pulsants animés par technologie (5G 🔵 / 4G 🟢 / 3G 🟠 / Saturée 🔴)
- Zones de couverture visibles autour de chaque antenne
- Tooltip détaillé au survol : opérateur, technologie, taux de charge
- Filtres par technologie (Toutes / 5G / 4G / 3G)
- Statistiques de couverture nationale (4G 94%, 5G 78%, 3G 99%, 62k sites)

### 🕓 Historique
- Conservation des **6 derniers tests**
- Suppression individuelle de chaque test (animation de glissement)
- Bouton **"Tout effacer"** avec animation en cascade
- Compteur de tests enregistrés
- Note de qualité **A / B / C** par test

---

## 🛠️ Installation

Aucune installation requise.

```bash
# Cloner le dépôt
git clone https://github.com/votre-pseudo/netpulse.git

# Ouvrir dans le navigateur
open netpulse.html
# ou double-cliquer sur le fichier
```

> ✅ Compatible Chrome, Firefox, Edge, Safari — aucune connexion internet requise (sauf pour charger les polices Google Fonts au premier lancement).

---

## 🎨 Stack technique

| Technologie | Usage |
|---|---|
| **HTML5** | Structure et markup sémantique |
| **CSS3** | Design system, animations, responsive |
| **JavaScript (ES6+)** | Logique de test, rendu dynamique, SVG |
| **Chart.js** | Graphique de comparaison opérateurs |
| **Google Fonts** | Outfit + Space Mono |

---

## 📁 Structure du projet

```
netpulse/
└── netpulse.html    # L'intégralité du projet en un seul fichier
```

---

## 📸 Aperçu des onglets

| Onglet | Description |
|---|---|
| **Test vitesse** | Jauge, métriques en temps réel, bouton GO animé |
| **Opérateurs** | Classement interactif + graphique Chart.js |
| **Carte antennes** | Carte SVG France avec antennes interactives |
| **Historique** | Liste des tests avec suppression individuelle ou globale |

---

## ⚠️ Note

Les données affichées (vitesses, latences, opérateurs, antennes) sont **simulées à titre indicatif** et ne reflètent pas votre connexion réelle. NetPulse est un projet de démonstration UI/UX.

---

## 📄 Licence

Distribué sous licence **MIT**. Voir le fichier [LICENSE](LICENSE) pour plus d'informations.

---

<div align="center">

Fait avec ❤️ · **NetPulse v1.0**

</div>
