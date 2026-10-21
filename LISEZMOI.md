# Dino Parc

1. Crée un dépôt GitHub et envoie-y tout le contenu de ce dossier (y compris le dossier .github).
2. Onglet Actions > "Build APK" > Run workflow (ou simplement un push).
3. Une fois terminé (quelques minutes), ouvre l'exécution et télécharge l'artefact "dino-parc-apk" : il contient app-debug.apk.
4. Installe l'APK sur ton téléphone (autorise les sources inconnues).

Pour tester sans APK : ouvre www/index.html dans le navigateur du téléphone.
Sauvegarde automatique dans l'appareil (localStorage).


## Nouveautés v6 : plusieurs cartes
- 4 cartes agrandies : Prairie (16×20), Jungle (18×22), Désert et canyon (20×24), Île volcanique (22×26).
- Chaque carte a des objectifs obligatoires (pour ouvrir la suivante) et des objectifs bonus (étoiles ⭐ et argent).
- Chaque carte repart de zéro ; succès, fossiles et quiz sont partagés. Une minicarte permet de se déplacer.
- Les anciennes sauvegardes sont reprises dans la Prairie.

## Icône
Le logo (tête de T-Rex) est dans le dossier assets/ : l'icône Android est générée automatiquement à la compilation.
