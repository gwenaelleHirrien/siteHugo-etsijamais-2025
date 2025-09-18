# Et si jamais – Hugo Starter (PaperMod)

Ce dossier est un **starter Hugo** prêt pour ton site "Et si jamais".
Il utilise le thème **PaperMod** et une structure en **français**.

## ⚙️ Prérequis
- Hugo Extended (0.100+)
- Git

## 🚀 Démarrer
```bash
# Dans le dossier du projet
git init
git submodule add https://github.com/adityatelange/hugo-PaperMod themes/PaperMod

# Lancer en local
hugo server -D
```

Le site sera accessible sur http://localhost:1313

## 🧱 Structure
- `content/` pages (accueil, services, blog, contact)
- `assets/css/custom.css` style personnalisé (vert #226622)
- `static/images/` images (place ton logo en /images/logo.png)
- `config.toml` configuration PaperMod
- `netlify.toml` prêt pour Netlify

## 🌐 Déploiement
- **Netlify** : connecte ton repo → Build: `hugo --gc --minify` ; Publish: `public/`  
- **GitHub Pages** : action GH pour builder et publier `./public`

## ✉️ Formulaire de contact
La page `/contact/` est compatible **Netlify Forms**. Si tu déploies ailleurs, remplace par un Google Form.

Bon build ! 🌿