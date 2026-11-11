# TP Vue.js 6, 7 et 9 — mise à jour du 11/11/2026

## TP 6 — Mini-annuaire d'étudiants

Application Vue 3 et Vite : ajout d'étudiants, recherche, tri, navigation vers une fiche et modification. Les données sont en mémoire et réinitialisées au rechargement.

```sh
cd "TP-ERRAFIY&SAADEDDINE/TP6"
npm ci
npm run dev
```

## TP 7 — Explorateur de pays

Liste de pays, recherche et page de détail à partir de l'API [countries.dev](https://countries.dev/docs). L'ancienne API de l'énoncé n'est plus disponible sans clé. L'API utilisée fournit le nom local plutôt que le nom officiel.

```sh
cd "TP-ERRAFIY&SAADEDDINE/TP7"
npm ci
npm run dev
```

## TP 9 — Météo en direct

Recherche de ville, météo actuelle et prévisions ; géolocalisation et historique local en bonus.

Copier `TP-ERRAFIY&SAADEDDINE/TP9/.env.example` vers `TP-ERRAFIY&SAADEDDINE/TP9/.env` et y indiquer sa clé OpenWeatherMap avant de lancer le projet. Ne jamais publier `.env`. Une clé `VITE_` est accessible au navigateur et ne constitue pas un secret côté client. Après modification de `.env`, redémarrer le serveur.

```sh
cd "TP-ERRAFIY&SAADEDDINE/TP9"
npm ci
npm run dev
```

Pour chaque projet, ouvrir l'adresse affichée par Vite. Sous PowerShell, si `npm` est bloqué, utiliser `npm.cmd` à la place. Pour compiler : `npm run build`.



