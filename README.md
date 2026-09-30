# Culture Gé — voix Siwis

Fichiers audio lus par [Culture Gé](https://romaindetroyat.github.io/culture-ge/) : chaque question
(avec sa catégorie), chaque réponse et les phrases de verdict, synthétisées à l'avance.

- Adresse d'un fichier : `https://romaindetroyat.github.io/culture-ge-voix/<xx>/<clé>.mp3`, où la clé
  est un hachage du texte lu (voir `scripts/voix.py` et `cleVoix()` dans `app/app.js` du dépôt
  [culture-ge](https://github.com/romaindetroyat/culture-ge)).
- Publication : GitHub Pages, depuis la branche `main` (dossier racine).
- Pour ajouter les fichiers des textes nouveaux ou modifiés :
  `python3 scripts/voix.py produire ../culture-ge-voix chemin/fr_FR-siwis-medium.onnx` depuis culture-ge.

## Crédits

Voix **Siwis** (`fr_FR-siwis-medium`), synthèse [Piper](https://github.com/rhasspy/piper).
Le modèle est entraîné sur le corpus SIWIS (Honnet et al., 2017) et diffusé sous licence
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) ; ces fichiers audio sont diffusés sous la
même licence.
