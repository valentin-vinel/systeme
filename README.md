# Portfolio — Développeur Web Freelance

Site one-page construit avec [Astro](https://astro.build) — rapide, léger, zéro JS inutile.

## 🚀 Démarrage rapide

```bash
npm install
npm run dev       # http://localhost:4321
npm run build     # Build de production dans /dist
npm run preview   # Prévisualiser le build
```

## 📁 Structure du projet

```
src/
├── components/
│   ├── Hero.astro          # Section d'accroche
│   ├── Stats.astro         # Bande de statistiques
│   ├── Offers.astro        # Vos offres & tarifs
│   ├── Projects.astro      # Vos réalisations
│   ├── Process.astro       # Étapes de travail
│   ├── Testimonials.astro  # Avis clients
│   ├── Contact.astro       # Formulaire de contact
│   └── Divider.astro       # Séparateur de section
├── layouts/
│   └── Layout.astro        # Nav, footer, scripts globaux
├── pages/
│   └── index.astro         # Page principale (assemble tout)
└── styles/
    └── global.css          # Variables CSS, reset, utilitaires
public/
└── favicon.svg
```

## ✏️ Personnalisation

### Infos personnelles
- **`src/layouts/Layout.astro`** — Votre prénom dans la nav et le footer
- **`src/components/Hero.astro`** — Remplacez l'emoji par votre vraie photo
- **`src/components/Contact.astro`** — Votre téléphone et ville

### Contenu
- **`src/components/Offers.astro`** — Modifiez les prix et prestations
- **`src/components/Projects.astro`** — Ajoutez vos vrais projets (URL + description)
- **`src/components/Testimonials.astro`** — Vos vrais témoignages clients
- **`src/components/Stats.astro`** — Vos stats réelles

### Formulaire de contact
Dans `Contact.astro`, remplacez `action="#"` par :
- **Formspree** : `https://formspree.io/f/VOTRE_ID` (gratuit, simple)
- **Netlify Forms** : ajoutez `netlify` dans la balise `<form>`

### Couleurs
Dans `src/styles/global.css`, modifiez les variables CSS :
```css
--accent: #1A472A;        /* Vert foncé */
--accent-bright: #2D7A47; /* Vert vif */
```

## 🌐 Déploiement

### Vercel (recommandé)
```bash
npm i -g vercel
vercel
```

### Netlify
Glissez le dossier `/dist` sur [app.netlify.com](https://app.netlify.com/drop)

### GitHub Pages
Ajoutez dans `astro.config.mjs` :
```js
export default defineConfig({
  site: 'https://votre-username.github.io',
  base: '/portfolio',
});
```
