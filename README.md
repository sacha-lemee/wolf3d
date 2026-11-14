# WOLF3D

### Development

By *Sacha Lemée*(sacha.lemee@epitech.eu), *Marin Jeunot*(marin.jeunot@epitech.eu) & *Armand Cambot*(armand.cambot@epitech.eu), the Paradise Devs team.

## Objective

**Paradise Palm 3D** is a first-person shooter set in a tropical, mysterious and stylized world. Built on raycasting, it lets the player explore several maps with a flashlight and weapons, guided by a full interface: HUD, main menu and settings, with a soundtrack.

## Features

- Raycasting engine with textured walls
- Six maps in `ressources/Wolf3D_LVLS/`
- Flashlight, several weapons with ammo and crosshair, sprint
- HUD, main menu, settings screen and soundtrack

## Getting Started

### Prerequisites

This project requires:
- `gcc` and `make`
- **CSFML 2.5 or 2.6** (CSFML 3 is not supported)

```sh
# Ubuntu / Debian
sudo apt install build-essential libcsfml-dev
# Fedora
sudo dnf install gcc make CSFML-devel
```

### Installation for Linux

1. **Clone the repository:**

```sh
git clone git@github.com:sacha-lemee/wolf3d.git
cd wolf3d
```

2. **Build the project:**

```sh
make
```

3. **Run the game:**

```sh
./wolf3d                                  # default map
./wolf3d ressources/Wolf3D_LVLS/stage1    # or a given map
```

### Controls (AZERTY)

| Action | Key |
|---|---|
| Move forward | `Z` |
| Move backward | `S` |
| Strafe left | `Q` |
| Strafe right | `D` |
| Turn left | `<` |
| Turn right | `>` |
| Flashlight | `F` |
| Shoot | `E` |
| Change weapon | `K` `L` `M` `O` |
| Sprint | `Left Shift` |

## Epitech warning

This project was built for the Epitech curriculum. **Epitech students: do not copy this code for your own project.** Copying is forbidden at Epitech and is treated as cheating. Read it to learn if you want, but write your own.

## Contributing

Contributions are welcome: read [CONTRIBUTING.md](CONTRIBUTING.md) and the [code of conduct](CODE_OF_CONDUCT.md).

## License

This project is licensed under the **MIT License**, see [LICENSE](LICENSE).

![WOLF3D License : MIT](https://img.shields.io/badge/License-MIT-blue.svg)
