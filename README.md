# KickLab (Android)

Générateur de grosse caisse aléatoire par-dessus un groove de charleston/caisse
claire fixe, avec lecture audio et export vers Groove Scribe.

## Obtenir l'APK

1. Crée un dépôt GitHub et envoie TOUT le contenu de ce dossier À LA RACINE du
   dépôt (pas dans un sous-dossier). Le dossier `.github` est caché : s'il
   n'apparaît pas après un glisser-déposer, crée-le à la main sur GitHub avec
   "Add file" > "Create new file", en nommant le fichier
   `.github/workflows/build-apk.yml` et en collant son contenu.
2. Vérifie dans l'onglet **Code** du dépôt que tu vois bien, à la racine :
   `package.json`, `capacitor.config.json`, `www/index.html` et `.github`.
3. Va dans l'onglet **Actions** : le build démarre tout seul (3 à 6 minutes).
4. Une fois la coche verte affichée, ouvre **Releases** (colonne de droite de
   la page du dépôt) puis "Dernière version", et télécharge `kicklab.apk`
   depuis ton téléphone.
5. Ouvre le fichier téléchargé et autorise l'installation quand Android le
   demande.

## Modifier l'appli

Le code est dans `www/index.html`. Chaque envoi sur GitHub relance le build
et remplace l'APK dans les Releases.
