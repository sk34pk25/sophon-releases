# SOPHON — installeurs

Ce dépôt ne contient que les versions publiées de SOPHON : les installeurs pour macOS et Windows, et le fichier qui permet à l'application de se mettre à jour toute seule. Le code de SOPHON est ailleurs.

## Dernière version

[SOPHON 10.2.0](https://github.com/sk34pk25/sophon-releases/releases/tag/Sophon-V10.2.0) améliore la vision locale, la reprise après compression, la conversation vocale et les rappels.

## Installer

Ouvre la dernière version dans [Releases](https://github.com/sk34pk25/sophon-releases/releases) et télécharge :

- **macOS, puce Apple** : `SOPHON-<version>-macOS-arm64.dmg`
- **macOS, processeur Intel** : `SOPHON-<version>-macOS-x64.dmg`
- **Windows** : `SOPHON-<version>-Windows-x64-Setup.exe`

Sur macOS, glisse SOPHON dans Applications, puis ouvre-le une première fois avec clic droit → Ouvrir : l'application n'est pas encore signée par un éditeur.

## Mises à jour

Une fois installé, SOPHON vérifie lui-même s'il existe une version plus récente, la télécharge et l'installe depuis l'application (Réglages → Mise à jour). Tes données (bots, mémoire, modèles) ne sont pas touchées.

Chaque version contient `sophon-update.json`, qui décrit ses fichiers avec leur taille et leur empreinte SHA-256 : l'application vérifie chaque téléchargement avant de l'installer.
