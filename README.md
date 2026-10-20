# SodiClub – Plateforme de gestion des réductions

Application web de gestion des clients, partenaires, réductions et vérification par QR code.

## Technologies

- React 18 + TypeScript
- Vite
- Tailwind CSS + shadcn/ui
- Supabase (base de données, authentification, fonctions serveur)

## Installation

Prérequis : Node.js 18+ et npm.

```sh
git clone <URL_DU_DEPOT>
cd <NOM_DU_DOSSIER>
npm install
npm run dev
```

## Build de production

```sh
npm run build
```

Les fichiers générés se trouvent dans `dist/`.

## Configuration

Variables d'environnement (fichier `.env`) :

```
VITE_SUPABASE_URL=...
VITE_SUPABASE_PUBLISHABLE_KEY=...
VITE_SUPABASE_PROJECT_ID=...
```

## Déploiement

Hébergé sur Netlify (build : `npm run build`, dossier : `dist`). Le fichier `public/_redirects` gère les routes de l'application.
