# Module 8 — Initiation au Terminal

**Objectifs :** comprendre ce qu'est le Terminal et utiliser les commandes de base en sécurité.

## 1. Ouvrir le Terminal

Spotlight (`⌘ Espace`) › « Terminal », ou Applications › Utilitaires › Terminal.

Le shell par défaut de macOS est **zsh**. L'invite ressemble à :

```
prenom@MacBook-Air ~ %
```

`~` désigne votre dossier personnel (`/Users/prenom`).

## 2. Se déplacer

| Commande | Rôle |
|----------|------|
| `pwd` | Afficher le dossier courant |
| `ls` | Lister le contenu (`ls -la` pour tout voir, fichiers cachés compris) |
| `cd Documents` | Entrer dans un dossier |
| `cd ..` | Remonter d'un niveau |
| `cd ~` ou `cd` | Revenir au dossier personnel |

Astuce : `Tab` complète automatiquement les noms de fichiers et de dossiers.

## 3. Manipuler des fichiers

| Commande | Rôle |
|----------|------|
| `mkdir essais` | Créer un dossier |
| `touch note.txt` | Créer un fichier vide |
| `cp note.txt copie.txt` | Copier |
| `mv copie.txt essais/` | Déplacer ou renommer |
| `cat note.txt` | Afficher le contenu |
| `rm fichier` | Supprimer **définitivement** (pas de corbeille !) |

## 4. Commandes propres à macOS

| Commande | Rôle |
|----------|------|
| `open .` | Ouvrir le dossier courant dans le Finder |
| `open -a "TextEdit" note.txt` | Ouvrir un fichier avec une application |
| `pbcopy` / `pbpaste` | Copier vers / coller depuis le presse-papiers (`ls \| pbcopy`) |
| `say "Bonjour"` | Faire parler le Mac |
| `caffeinate` | Empêcher la mise en veille (`Ctrl C` pour arrêter) |
| `sw_vers` | Afficher la version de macOS |
| `softwareupdate -l` | Lister les mises à jour disponibles |

## 5. Obtenir de l'aide

- `man ls` affiche le manuel d'une commande (`q` pour quitter).
- `Ctrl C` interrompt une commande en cours.
- `↑` rappelle les commandes précédentes.

## 6. Prudence

- `sudo` exécute une commande avec les droits administrateur : ne l'utiliser que si l'on comprend la commande.
- Ne jamais copier-coller une commande trouvée sur Internet sans savoir ce qu'elle fait.
- `rm -r` supprime un dossier entier sans passer par la corbeille.

## Exercice

1. Ouvrez le Terminal et affichez le dossier courant.
2. Créez un dossier `essais-terminal` dans Documents et placez-vous dedans.
3. Créez un fichier `bonjour.txt` contenant « Bonjour » : `echo "Bonjour" > bonjour.txt`.
4. Affichez son contenu, puis ouvrez le dossier dans le Finder avec `open .`.
5. Affichez votre version de macOS avec `sw_vers`.

⬅️ [Module 7](07-securite.md) · 🏠 [Retour au sommaire](../README.md)
