# 🚢 Warship Battle By C02

Bataille navale multijoueur dans le navigateur : **aucun téléchargement, aucune inscription obligatoire**.

### ▶️ [Jouer maintenant](https://Ghoster-001.github.io/warship-battle-by-c02/)

![Menu du jeu](captures/menu.png)

![Une partie en cours](captures/combat.png)

## Fonctionnalités

- 🤖 **Contre l'IA** : 4 niveaux (Facile, Moyen, Difficile, Champion)
- 🌍 **Adversaire aléatoire** et 🔑 **salons privés** avec un code à 6 caractères
- 📐 Grille de **6×6 à 15×15**, flotte personnalisable, chronomètre par tour (mode Blitz)
- ⚡ **5 boosts tactiques** gagnés en coulant des navires :
  🛡️ Protection d'une case · 🚀 Torpille 2×2 · 📡 Sonar 2×2 · 💣 Mine · ⚓ Déplacement
- 🏆 Niveaux, grades, statistiques, avatars (photo ou GIF) et 15 couleurs d'interface
- 🔒 Parties équitables : chaque joueur est seul à connaître sa flotte, les tirs sont arbitrés par le défenseur
  et la flotte est vérifiée en fin de partie

## Jouer avec un ami

1. Ouvrez le lien du jeu (chacun de votre côté).
2. L'un clique sur **Hôte** et partage le code à 6 caractères.
3. L'autre clique sur **Rejoindre une partie** et saisit le code.

Les parties passent par des **relais publics gratuits** (courtiers MQTT sur connexion sécurisée), ce qui fonctionne
depuis presque n'importe quel réseau (Wi-Fi, 4G/5G). Y transitent le pseudo, une miniature d'avatar et les tirs, jamais la
position des navires. Si ces relais sont bloqués par un réseau très restrictif, le jeu essaie une connexion directe en secours.

## Pour les curieux

Le jeu tient dans un seul fichier, `index.html`. Le dossier du projet contient aussi un petit serveur optionnel
(`server.js`) pour des comptes en ligne et un relais des parties.

*Warship Battle By C02*