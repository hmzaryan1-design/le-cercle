# Le Cercle Casablanca

Landing page React/Vite pour Le Cercle Casablanca.

## Installation

```bash
npm install
npm run dev
```

## Build production

```bash
npm run build
```

Le dossier de sortie est `dist`.

## Déploiement Vercel

- Framework: Vite
- Build command: `npm run build`
- Output directory: `dist`

## Déploiement Netlify

- Build command: `npm run build`
- Publish directory: `dist`

## Formulaire Make.com

Dans `src/App.jsx`, cherche :

```js
// await fetch("https://hook.eu1.make.com/YOUR_WEBHOOK_ID", {
```

Remplace `YOUR_WEBHOOK_ID` par ton webhook Make.com, puis décommente le bloc `fetch`.

## Domaine

Prévu pour : `lecerclecasablanca.com`
