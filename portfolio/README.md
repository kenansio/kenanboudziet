# Portfolio BTS SIO SISR — Épreuve E5

Portfolio professionnel pour l'épreuve E5 "Support et mise à disposition de services informatiques".

## Structure des fichiers

```
portfolio/
├── index.html          ← Page d'accueil (présentation + liens)
├── realisations.html   ← Réalisations professionnelles (stage + TP)
├── veille.html         ← Veille technologique
├── synthese.html       ← Tableau de synthèse des compétences
├── style.css           ← Feuille de style partagée
├── assets/
│   ├── cv.pdf                  ← Ton CV (à ajouter)
│   └── tableau_synthese.pdf    ← Tableau de synthèse officiel (à ajouter)
└── README.md
```

## 🚀 Héberger sur GitHub Pages (tuto complet)

### Étape 1 — Créer un compte GitHub
1. Va sur [github.com](https://github.com) et crée un compte si tu n'en as pas.

### Étape 2 — Créer un nouveau dépôt (repository)
1. Clique sur le bouton vert **"New"** (ou **"+"** en haut à droite > New repository)
2. Nom du dépôt : `portfolio-bts-sio` (ou ce que tu veux)
3. Laisse-le en **Public** (obligatoire pour GitHub Pages gratuit)
4. Clique sur **"Create repository"**

### Étape 3 — Uploader tes fichiers
1. Dans ton dépôt vide, clique sur **"uploading an existing file"**
2. Glisse-dépose TOUS tes fichiers (`index.html`, `realisations.html`, `veille.html`, `synthese.html`, `style.css`) et le dossier `assets/`
3. En bas, écris un message de commit : "Ajout portfolio E5"
4. Clique sur **"Commit changes"**

### Étape 4 — Activer GitHub Pages
1. Dans ton dépôt, clique sur **"Settings"** (onglet en haut)
2. Dans le menu gauche, clique sur **"Pages"**
3. Sous "Source", sélectionne **"Deploy from a branch"**
4. Branche : **main** · Dossier : **/ (root)**
5. Clique sur **"Save"**

### Étape 5 — Accéder à ton site
Après 1-2 minutes, ton portfolio sera accessible à l'adresse :
```
https://kenansio.github.io/kenanboudziet/
```
GitHub te l'affiche aussi dans Settings > Pages.

### Mettre à jour le site
À chaque modification, retourne dans ton dépôt GitHub, clique sur le fichier à modifier > icône crayon ✏️, modifie, puis "Commit changes". Les changements s'appliquent en quelques secondes.

---
## ✏ Checklist des zones à personnaliser

- [ ] `index.html` : Prénom, NOM, lycée, entreprises de stage, email, lien LinkedIn
- [ ] `index.html` : Lien LinkedIn dans `href="https://linkedin.com/in/TON-PROFIL"`
- [ ] `index.html` : Email dans `href="mailto:ton.email@exemple.fr"`
- [ ] `realisations.html` : Titres, contextes, tâches, outils, bilans des 2 réalisations
- [ ] `veille.html` : Outils de veille utilisés, articles analysés, bilan
- [ ] `synthese.html` : Points (●/◑/○) selon tes compétences réellement mobilisées
- [ ] `assets/cv.pdf` : Ajouter ton CV en PDF
- [ ] `assets/tableau_synthese.pdf` : Ajouter le tableau officiel rempli
- [ ] Toutes les pages footer : remplacer "Prénom NOM"
