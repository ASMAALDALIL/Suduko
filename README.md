# 🧩 Sudoku Game — Python & Pygame

Une application complète de Sudoku développée en Python avec Pygame, offrant plusieurs modes de jeu dont un solveur IA avec visualisation en temps réel.

## ✨ Fonctionnalités

- **Mode Classique** — 3 niveaux de difficulté : Facile, Moyen, Difficile
- **Solveur IA** — Résolution automatique avec algorithme Backtracking animé en temps réel (cases vertes = placement, cases rouges = retour arrière)
- **Mode IA personnalisé** — L'utilisateur saisit sa propre grille et l'IA la résout
- **Mode Multijoueur en réseau** — 2 joueurs sur le même réseau local (architecture client/serveur avec sockets)
- **Sauvegarde & Reprise** — Possibilité de sauvegarder et reprendre une partie
- **Système d'aide** — Indices disponibles en cours de jeu
- **Chronomètre** — Suivi du temps de jeu

## 🛠️ Technologies utilisées

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pygame](https://img.shields.io/badge/Pygame-3776AB?style=flat&logo=python&logoColor=white)

- **Python 3.12**
- **Pygame** — Interface graphique
- **Sockets TCP** — Communication réseau multijoueur
- **Threading** — Gestion des connexions réseau en parallèle
- **JSON / TXT** — Sauvegarde des grilles

## 🤖 Algorithme IA

Le solveur utilise le **Backtracking (retour arrière)** :
1. Parcourt chaque cellule vide
2. Essaie les chiffres de 1 à 9
3. Vérifie la validité (ligne, colonne, carré 3×3)
4. Revient en arrière si aucun chiffre n'est valide
5. Visualise chaque étape en temps réel à l'écran
## 🚀 Lancer le projet

### Prérequis
```bash
pip install pygame
```

### Lancement
```bash
cd sudoku
python main.py
```

## 👥 Équipe

| Nom | GitHub |
|-----|--------|
| Asma Al Dalil | [@ASMAALDALIL](https://github.com/ASMAALDALIL) |
| Meryem Al Moumi | [@MeryemAlMoumi](https://github.com/MeryemAlMoumi) |
