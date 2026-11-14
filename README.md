🏝️ PARADISE PALM 3D 🏝️

Paradise Palm 3D est un jeu de tir à la première personne (FPS) situé dans un univers tropical, mystérieux et stylisé. À travers un système de raycasting, le joueur explore différentes cartes, équipé d'une lampe torche, d'armes, et guidé par une interface utilisateur complète avec HUD, menu principal, et paramètres personnalisables. Le tout accompagné d’une bande sonore immersive. 🏝️

[AZERTY]
| Action           | Touche             |
| ---------------- | ------------------ |
| Avancer          | `Z`                |
| Reculer          | `S`                |
| Strace à gauche  | `Q`                |
| Strace à droite  | `D`                |
| Tourner à gauche | `<`                |
| Tourner à droite | `>`                |
| Allumer lampe    | `F`                |
| Tirer            | `E`                |
| Changer d'arme   | `K` `L` `M` `O`    |
| Sprint           | `LShift`           |

## Installation (Linux)

Prérequis : `gcc`, `make` et **CSFML 2.5 ou 2.6** (la version 3 n'est pas compatible).

```sh
# Ubuntu / Debian
sudo apt install build-essential libcsfml-dev
# Fedora
sudo dnf install gcc make CSFML-devel
```

```sh
git clone git@github.com:sacha-lemee/wolf3d.git
cd wolf3d
make
./wolf3d                                        # carte par défaut
./wolf3d ressources/Wolf3D_LVLS/stage1          # ou une carte précise
```

Projet réalisé par l'équipe Paradise Devs : LEMEE SACHA, JEUNOT MARIN ET ARMAND CAMBOT
