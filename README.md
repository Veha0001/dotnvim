# AstroNvim Template

<!--**NOTE:** This is for AstroNvim v4+-->

A template for getting started with [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## 🛠️ Installation

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
```
## Termux

### Install Required Packages

Run the following command to install the necessary packages in Termux:

```bash
apt update && apt upgrade
apt install termux-api python neovim git nodejs-lts fd ripgrep ruff stylua luarocks lua-language-server yarn fzf clang termux-tools lazygit
```

### Termux clipboards

For get clipboards from vim to the device.

> Install packages: `apt install termux-api`.
> Then install Termux:API app from **Github** or **F-Dorid**.

> [!NOTE]
> No need to install **Termux:API** for **Termux Play Store**.

#### Create a new user repository from this template

Press the "Use this template" button above to create a new repository to store your user configuration.

You can also just clone this repository directly if you do not want to track your user configuration in GitHub.

#### Clone the repository

```bash
git clone https://github.com/Veha0001/dotAstroNvim ~/.config/nvim
```

#### Start Neovim

```bash
nvim
```
