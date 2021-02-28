[![GitHub Actions Status](https://github.com/jaydwayne/neopo/workflows/python-pip/badge.svg)](https://github.com/jaydwayne/neopo/actions)

# neopo
## A lightweight solution for local Particle development.

![Neopo Screenshot](https://d33wubrfki0l68.cloudfront.net/d9a010fe28827ee5728e18eaea93a00ee7631208/1833f/assets/images/neopo-carbon.png)

## Features

- Builds Particle projects locally without any overhead.
- Compatible with Particle Workbench and Particle CLI.
- Installs and manages necessary Particle dependencies.
- Built with Python using only the standard library.
- Supports Linux, macOS, Windows, and Raspberry Pi.
- Supports tab completion to assist development.

## Installation

Universal Installer (Linux/macOS):

```bash
$ bash <(curl -sL neopo.xyz/install)
```

Install from [AUR](https://aur.archlinux.org/packages/neopo-git/):

```bash
$ yay -S neopo-git
$ neopo install
```

Install from source (pip):

```bash
$ git clone https://github.com/jaydwayne/neopo
$ cd neopo
$ sudo python3 -m pip install .
$ neopo install
```


For more installation information, please refer to the [Installation tutorial.](https://neopo.xyz/tutorials/install)

## Usage

To get started with neopo, please refer to the [Quick Reference.](https://neopo.xyz/docs/quick-docs)

For descriptions of all available commands, please refer to the [Complete Reference.](https://neopo.xyz/docs/full-docs)
