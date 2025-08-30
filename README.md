# Landing Page Château de Cranne

Ce dépôt contient une landing page simple pour le Château de Cranne.

## Affichage de la page

1. Placez vos photos dans le dossier `assets/` à la racine du dépôt.
2. Ouvrez le fichier `index.html` directement dans votre navigateur.
3. Les images seront affichées automatiquement sur la page si elles sont référencées correctement dans le code.

## Déploiement sur GitHub Pages

- Allez dans les paramètres du dépôt (`Settings > Pages`).
- Sélectionnez la branche `main` et le dossier `/` (racine) pour activer GitHub Pages.
- L’URL de la page sera :  
  `https://chateaudecranne-crypto.github.io/landingcireuse/`

## Structure recommandée

```
/
├── assets/
│   ├── photo1.jpg
│   └── photo2.jpg
├── index.html
└── README.md
```

## Conseils pour les images

- Mettez vos photos dans le dossier `assets/`.
- Dans `index.html`, utilisez des chemins relatifs comme :
  ```html
  <img src="assets/photo1.jpg" alt="Photo 1">
  <img src="assets/photo2.jpg" alt="Photo 2">
  ```
- Vérifiez que le nom des fichiers (majuscules/minuscules, extension) correspond exactement à celui dans le dossier.

## Problèmes fréquents

- **404 ou images cassées** : Vérifiez le chemin et l’orthographe du nom du fichier image.
- **Pas d’index.html** : Il doit être à la racine du dépôt.

---
