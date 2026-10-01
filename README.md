# ALEF MEDIA GROUP (AMG) - Développement & Formations

Ce projet est la copie 100% autonome, réactive et fidèle à l'identique du site [https://www.alefmediagroup.com/](https://www.alefmediagroup.com/).

---

## 🎨 Aperçu des Animations 3D & Visuels

Les animations 3D fluides (formes géométriques en rotation) intégrées au site :

<div align="center">
  <img src="assets/images/animation-3d-torus.gif" width="280" alt="Animation 3D Torus" />
  <img src="assets/images/animation-3d-sphere.gif" width="280" alt="Animation 3D Sphère" />
  <img src="assets/images/animation-3d-cube.gif" width="280" alt="Animation 3D Géométrie" />
</div>

<div align="center">
  <sub>Formes 3D animées abstraites intégrées en local et synchronisées sur GitHub</sub>
</div>

---

## 📁 Architecture du Projet

```
c:\alefmediagroup\
├── index.html                     # Page principale (HTML + CSS SSR + intégration composants)
├── index.original.html            # Sauvegarde de la version brute en ligne
├── server.js                      # Serveur HTTP local autonome haute performance (Node.js natif)
├── package.json                   # Configuration et commandes d'exécution
├── robots.txt                     # Directive d'indexation
├── sitemap.xml                    # Sitemap XML officiel
├── searchIndex-RcGsCp8zDJNg.json  # Index de recherche Framer
└── assets\
    ├── images\                    # Médias & GIFs 3D animés (torus, sphere, cube, logo pin, etc.)
    │   ├── animation-3d-torus.gif
    │   ├── animation-3d-sphere.gif
    │   ├── animation-3d-cube.gif
    │   ├── NmcynsjMQF6a2CPAvkeTlYv9WCs.gif
    │   ├── t0dKOnLrsxOlwzG29OJyQrEFroA.gif
    │   ├── 09wqCpAfeQJTtqSMwKrLqRh7Lq0.gif
    │   └── ... (icônes et logos PNG)
    ├── fonts\                     # Polices typographiques (Caprasimo, JetBrains Mono, Inter, Barcode)
    └── js\                        # Modules ESM React & Framer Motion hydratés en local
```

---

## 🚀 Lancement Rapide

### Option 1 : Avec Node.js (Recommandé)
```bash
npm start
```
Ou directement :
```bash
node server.js
```
Puis ouvrez votre navigateur sur [http://localhost:3000](http://localhost:3000).

### Option 2 : Avec Python
```bash
python -m http.server 3000
```

---

## ✨ Points Clés & Fonctionnalités
- **Formations Spécialisées** : Formations en Intelligence Artificielle (IA), Programmation (React, Python, Flutter) et Automatisation de workflows.
- **Zéro dépendance CDN externe** : Toutes les polices, GIFs animés 3D, icônes et scripts s'exécutent en local.
- **Animations 3D préservées** : Formes géométriques en rotation continue sans perte de fluidité.
- **Menu Interactif** : Déroulement au survol ET au clic/tap avec navigation fluide vers les sections.
- **Responsive Design** : Adapté aux écrans mobiles, tablettes, ordinateurs portables et grands écrans.
