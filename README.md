# Portfolio — Solène Crouzet

Version React/Vite préparée à partir du fichier JSX généré avec Claude.

## Lancer le site sur ton Mac

1. Installe Node.js si ce n'est pas déjà fait : https://nodejs.org/
2. Ouvre ce dossier dans VS Code.
3. Ouvre le Terminal intégré.
4. Lance :

```bash
npm install
npm run dev
```

Vite affichera ensuite une adresse locale (souvent http://localhost:5173) à ouvrir dans ton navigateur.

## Où modifier le portfolio ?

Le fichier principal est :

`src/App.jsx`

Au début du fichier, la constante `PROJECTS` contient tous les projets fictifs actuels (Ossature, Foudre, Nocturne, etc.). C'est la partie que tu remplaceras par tes vrais projets.

Les images peuvent être placées dans :

`public/images/`

## GitHub

Tu peux déposer l'intégralité de ce dossier dans un repository GitHub. Il contient déjà les fichiers nécessaires à un projet Vite.

## Mise en ligne

Le projet peut ensuite être relié facilement à Vercel ou Netlify. La commande de build est :

`npm run build`

Le dossier de sortie est :

`dist`
