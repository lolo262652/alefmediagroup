# ALEF MEDIA GROUP - Copie Conforme à l'Identique

Ce projet est la copie 100% autonome et fidèle à l'identique du site [https://www.alefmediagroup.com/](https://www.alefmediagroup.com/).

## 📁 Architecture du projet

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
    ├── images\                    # Ensemble des médias (GIFs 3D animés, icônes PNG, favicon)
    ├── fonts\                     # Ensemble des polices typographiques (Caprasimo, JetBrains Mono, Inter, Barcode)
    └── js\                        # Modules ESM React & Framer Motion hydratés en local
```

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

## ✨ Caractéristiques de la copie
- **Zéro dépendance CDN externe** : Toutes les polices, images 3D, icônes et scripts s'exécutent en local.
- **Animations 3D préservées** : Formes géométriques en rotation, micro-interactions, typographie fidèle.
- **Responsive Design** : Adapté aux écrans mobiles, tablettes et ordinateurs de bureau.
- **Navigation et Sections** : Services, Formations, Expériences, Coordonnées, Modalités de contact.
