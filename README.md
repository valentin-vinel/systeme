# My system web app

Site one-page construit avec [Astro](https://astro.build).

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