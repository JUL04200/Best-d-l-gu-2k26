# Site de campagne — Délégués de classe

Site statique (HTML/CSS/JS, aucune dépendance) pour la campagne de :

- **Jules Arrouasse** — délégué titulaire
- **Benjamin Tubiana** — délégué suppléant

## Structure

- `index.html` — page d'accueil (hero, présentation du binôme, pourquoi voter, engagements, FAQ)
- `jules.html` — page de présentation de Jules
- `benjamin.html` — page de présentation de Benjamin
- `css/style.css` — styles
- `js/script.js` — menu mobile + accordéon FAQ
- `images/` — photos des candidats (voir `images/README.md`)

## Ajouter les photos

Déposez `jules.jpg` et `benjamin.jpg` dans le dossier `images/`. Elles remplaceront automatiquement les avatars avec initiales.

## Aperçu en local

Ouvrez simplement `index.html` dans un navigateur, ou lancez un petit serveur local :

```bash
python3 -m http.server 8000
```

puis ouvrez `http://localhost:8000`.
