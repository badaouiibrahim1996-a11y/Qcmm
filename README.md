# QCM Résidanat DZ — extraction OCR initiale

## Contenu
- `index.html` : interface responsive en français, compatible mobile.
- `questions.js` : blocs de questions détectés automatiquement sur les 73 pages, avec page, source connue, texte OCR brut et propositions lorsque leur séparation est possible.
- `data/pages.json` : transcription OCR de toutes les pages.
- `data/questions.json` : données extraites au format JSON.

## Publier sur GitHub Pages
1. Créer un dépôt GitHub.
2. Téléverser tous les fichiers et le dossier `data` à la racine du dépôt.
3. Ouvrir Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.

## Important — qualité de l'extraction
L'OCR a été exécuté sur les 73 pages. Il détecte 411 blocs numérotés, mais ce nombre ne signifie pas 411 questions propres : certains numéros sont mal lus, certaines pages sont des montages de plusieurs pages, et certaines questions/options peuvent être fusionnées, tronquées ou dupliquées. La transcription brute de chaque page est incluse pour faciliter la vérification.

Les sources clairement identifiables comprennent :
- Université Salah Boubnider Constantine 3, concours du résidanat du 12 octobre 2024 (pages PDF 17–36).
- Université Kasdi Merbah Ouargla, concours Résidanat Sud et Hauts Plateaux du 4 novembre 2023 (visible sur la page PDF 37 et pages suivantes du lot correspondant).
- D'autres pages dont l'université/la session ne sont pas confirmées.

## Corrigés
Cette version ne prétend pas fournir un corrigé validé pour les 411 blocs. Les corrections officielles ne sont indiquées que si elles sont réellement identifiées comme telles ; les annotations manuscrites des scans ne sont pas considérées automatiquement comme corrigé officiel. Le site signale les items qui nécessitent une correction et une validation médicale. Ne pas utiliser les textes OCR comme source clinique définitive sans relire le scan.

## Confidentialité
Le site fonctionne sans compte ni serveur. Les choix et l'historique de consultation restent dans le navigateur local.
