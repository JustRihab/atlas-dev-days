# Atlas Dev Days — Site web

Site vitrine de la première édition des **Atlas Dev Days**, une conférence de deux jours dédiée
aux développeurs web au Maroc : talks, ateliers pratiques et rencontres avec des entreprises.

Projet réalisé dans le cadre du **Brief 1 — Atlas Dev Days** (Sprint 1) : maquette Figma puis
intégration statique en **HTML5 sémantique** et **CSS3 natif**.

---

## 🔗 Liens

| Ressource | Lien |
|---|---|
| 💻 Dépôt GitHub | https://github.com/JustRihab/atlas-dev-days |
| 🎨 Maquette Figma (lecture seule) |  (https://www.figma.com/design/TEV5ueiMEUbnPLnN9mNlv1/Brief-1-Atlas-Dev-Days?node-id=55-180&t=QH2T3v9WwojeRdu7-1) |

---

## 📄 Pages du site

| Page | Fichier | Contenu |
|---|---|---|
| Accueil | `index.html` | Hero (nom, dates, lieu), chiffres clés, présentation, aperçu de 3 intervenants |
| Programme | `programme.html` | Programme des 2 journées (12 talks : horaire, titre, intervenant, thème) |
| Intervenants | `intervenants.html` | 6 cartes (photo, nom, poste, sujet du talk, réseau social) |
| Inscription | `inscription.html` | Formulaire complet (validation native) + infos pratiques |

## 🛠️ Stack technique

- **HTML5** — balises sémantiques (`header`, `nav`, `main`, `section`, `article`, `footer`)
- **CSS3** — fichier unique `css/style.css`
- **Accessibilité** — navigation clavier complète, états `:hover` / `:focus` visibles,
  labels reliés aux champs (`for` / `id`)
- **Git & GitHub** — commits conventionnels,
  déploiement via GitHub Pages

## 📁 Arborescence

```
atlas-dev-days/
├── index.html
├── programme.html
├── intervenants.html
├── inscription.html
├── css/
│   └── style.css
└── assets/
    └── images/
```


### Scores Lighthouse (audit du 09/10/2026)

| Page | Performance | Accessibilité | Bonnes pratiques | SEO |
|---|---|---|---|---|
| Accueil | — | — | — | — |
| Programme | — | — | — | — |
| Intervenants | | — | | |
| Inscription |  |  |  |  |
