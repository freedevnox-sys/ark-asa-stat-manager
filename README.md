# ARK Stat Manager

Outil Windows pour **ARK: Survival Ascended** : il répartit automatiquement les points de statistiques d'un personnage selon des **profils** (santé, endurance, poids, etc.), avec des contrôles de sécurité avant chaque application.

## Installation

1. Télécharge le ZIP de la dernière version dans [Releases](../../releases/latest).
2. Extrais-le où tu veux, puis lance `ARKStatManager.exe` (aucun Python requis).
3. Windows SmartScreen ou ton antivirus peut avertir : l'exécutable n'est pas signé numériquement. Compare son empreinte avec le fichier `..._SHA256.txt` fourni dans la release si tu veux vérifier ton téléchargement.

## Mises à jour

Le bouton **Mise à jour** de l'application cherche la dernière version stable publiée ici, la télécharge, vérifie sa taille et son empreinte SHA-256, sauvegarde tes profils et réglages, puis installe et relance, **uniquement après ta confirmation**. L'application vérifie aussi discrètement au démarrage (désactivable) : elle affiche seulement un repère sur le bouton, sans rien installer.

Les informations de version sont dans [`update.json`](update.json).

## Sécurité

- Arrêt d'urgence global : **Ctrl+F9**.
- Contrôle avant application (fenêtre ARK, calibration, curseur), clic test +1, arrêt si la souris est déplacée ou si ARK perd le focus.

## Avertissement

Cet outil automatise des clics dans le jeu. Vérifie que c'est autorisé par les règles du serveur sur lequel tu joues ; tu l'utilises à tes risques. Projet personnel, non affilié à Studio Wildcard.
