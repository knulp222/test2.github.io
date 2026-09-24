# Module 6 — Sauvegarde avec Time Machine

**Objectifs :** mettre en place une sauvegarde automatique et savoir restaurer un fichier.

## 1. Pourquoi sauvegarder ?

Panne, perte, vol, fausse manipulation : sans sauvegarde, les données sont perdues. Règle simple : **au moins deux copies de ses fichiers importants, dont une hors du Mac**.

## 2. Ce qu'il faut

- Un **disque externe** (idéalement au moins deux fois la capacité utilisée sur le Mac), ou
- Un disque réseau compatible Time Machine (NAS).

## 3. Configurer Time Machine

1. Brancher le disque externe.
2. Réglages Système › Général › **Time Machine**.
3. Cliquer sur **Ajouter un disque de sauvegarde…** et choisir le disque.
4. Activer le **chiffrement** de la sauvegarde (recommandé) et noter le mot de passe en lieu sûr.

⚠️ Le disque choisi peut être effacé et reformaté : ne pas utiliser un disque contenant des données à conserver.

Time Machine sauvegarde ensuite automatiquement : toutes les heures pour les dernières 24 h, chaque jour pour le mois écoulé, chaque semaine pour les mois précédents, tant qu'il reste de la place.

## 4. Restaurer un fichier

1. Ouvrir le dossier où se trouvait le fichier dans le Finder.
2. Lancer **Time Machine** (Spotlight ou icône dans la barre des menus › Parcourir les sauvegardes Time Machine).
3. Remonter dans le temps avec les flèches ou la frise à droite.
4. Sélectionner le fichier et cliquer sur **Restaurer**.

## 5. Et iCloud ?

iCloud Drive **synchronise** les fichiers : une suppression est répercutée sur tous les appareils (récupération possible pendant 30 jours via iCloud.com). Ce n'est donc pas un remplacement complet d'une vraie sauvegarde.

## Exercice

1. Configurez Time Machine sur un disque externe de test.
2. Lancez une sauvegarde manuelle (icône Time Machine › Sauvegarder maintenant).
3. Supprimez un fichier de test, videz la corbeille, puis restaurez-le avec Time Machine.

⬅️ [Module 5](05-applications.md) · ➡️ [Module 7 — Sécurité](07-securite.md)
