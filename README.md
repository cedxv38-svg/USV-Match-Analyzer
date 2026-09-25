# USV Match Analyzer Android

Projet Android natif qui embarque la V6.5 dans une WebView et permet de choisir un gros MP4 depuis le stockage Android.

## Compilation
1. Ouvrir ce dossier dans Android Studio.
2. Laisser Android Studio synchroniser Gradle.
3. Menu Build > Build APK(s).
4. APK généré dans `app/build/outputs/apk/debug/app-debug.apk`.

## Notes
- Internet est nécessaire pour charger TensorFlow.js et COCO-SSD au moment où tu appuies sur Charger IA.
- La vidéo reste locale sur le téléphone/tablette.
- Pour les fichiers de plusieurs Go, il faut suffisamment d'espace et un appareil assez puissant.

## Build automatique GitHub Actions
- Le projet contient `.github/workflows/build-apk.yml`.
- Dès qu'il est poussé dans ce dépôt, GitHub compile automatiquement l'APK.
- L'APK est ensuite disponible dans l'onglet Actions > dernier build > Artifacts > USV-Match-Analyzer-APK.
