# Dossier images (non versionné en binaire)

Ce projet évite de versionner des fichiers binaires d'images dans certains workflows d'extraction.

## Comment ajouter vos photos du kit

Placez vos photos dans ce dossier avec ces noms :

- `kit-principal.png`
- `kit-1.png`
- `kit-2.png`
- `kit-3.png`

La page `produit.html` est configurée pour les afficher automatiquement en cherchant, dans l'ordre :

1. dossier `images/`
2. dossier `image/`

Pour chaque nom, les extensions suivantes sont testées : `.png`, `.jpg`, `.jpeg`, `.webp`.
