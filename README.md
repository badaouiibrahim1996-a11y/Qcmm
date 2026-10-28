# QCM Résidanat DZ — version initiale

## Démarrage
- Ouvrir `index.html` dans un navigateur, ou publier le dépôt avec GitHub Pages.
- Aucune installation, serveur, compte, API ou base de données n'est nécessaire.
- Les favoris, le thème sombre et la progression sont conservés dans le stockage local du navigateur.

## Publication sur GitHub Pages
1. Créer un nouveau dépôt GitHub.
2. Décompresser ce ZIP et téléverser `index.html`, `questions.js` et `README.md` à la racine du dépôt.
3. Dans Settings → Pages, choisir « Deploy from a branch », branche `main`, dossier `/ (root)`, puis Save.
4. Attendre la génération du lien GitHub Pages.

## Ajouter des questions
Modifier `questions.js`. Chaque entrée suit la structure :
- `id`: identifiant unique.
- `subject`: matière.
- `year`: année ou « Non précisée » si inconnue.
- `university`: université / faculté si prouvée par la source.
- `reference`: référence lisible, par exemple « Résidanat 2024 · Université X ».
- `page`: numéro de page source.
- `mode`: `multiple` ou `single`.
- `question`, `options`: énoncé et propositions.
- `correct`: indices des propositions correctes, en commençant à zéro (A=0, B=1...).
- `correctionType`: `official` uniquement si le corrigé officiel est réellement identifié ; sinon `ai`.
- `explanation`, `optionNotes`, `tip`: explication, analyse des propositions et astuce.

## Limites de cette version
Le PDF fourni est un scan photographié de 73 pages. Cette version contient une première série de questions transcrites depuis la page 4/73, avec corrections IA proposées et signalées comme telles. Elle ne prétend pas avoir extrait, vérifié ou corrigé les 73 pages. Plusieurs formulations doivent être relues sur l'image originale, en particulier les items incomplets ou ambigus. Ne pas attribuer une année ou une université qui ne figure pas explicitement dans la source.

## Confidentialité
Le site ne collecte ni n'envoie aucune donnée. Les données de progression restent dans le navigateur utilisé.
