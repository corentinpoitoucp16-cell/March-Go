# MarchéGo — application Android

Cette version contient :
- le nouveau visuel MarchéGo ;
- une navigation Accueil / Rechercher / Favoris / Infos ;
- recherche par ville, village ou code postal ;
- géolocalisation GPS et tri des marchés par distance ;
- favoris enregistrés sur le téléphone ;
- écran de démarrage/logo MarchéGo ;
- build APK automatique via GitHub Actions.

## Installer sur le téléphone via GitHub
1. Mets tout le contenu de ce dossier dans ton dépôt GitHub MarchéGo.
2. Va dans **Actions**.
3. Lance **Build MarchéGo APK** avec **Run workflow**.
4. Une fois terminé, ouvre le résultat **MarcheGo-debug-apk** et récupère `app-debug.apk`.
5. Ouvre l'APK sur ton Samsung et autorise l'installation puis la localisation.

## Données
Le fichier `app/src/main/assets/marches.json` est le point d'entrée de la base des marchés.
Remplace son contenu par la base complète MarchéGo quand elle est prête.
