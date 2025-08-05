# Dotfiles

Personal configuration files for development environment setup.

## Overview

This repository contains my personal dotfiles and configuration files for various tools and applications. These configs help maintain a consistent development environment across different machines.

## Contents

- **`.zshrc`** - Zsh shell configuration with Oh My Zsh

## Features

### Zsh Configuration
- **Framework**: Oh My Zsh with `robbyrussell` theme
- **Plugins**: Comprehensive plugin setup including:
  - Development tools: `git`, `docker`, `terraform`, `aws`, `gh`
  - Node.js ecosystem: `node`, `npm`, `fnm`
  - Productivity: `fzf`, `tmux`, `vi-mode`, `zoxide`
  - Utilities: `copypath`, `emoji`, `web-search`, `ssh-agent`

## Installation

1. Clone this repository:
   ```bash
   git clone <repository-url> ~/configs
   ```

2. Backup existing configs:
   ```bash
   cp ~/.zshrc ~/.zshrc.backup
   ```

3. Create symlinks:
   ```bash
   ln -sf ~/configs/.zshrc ~/.zshrc
   ```

4. Reload your shell:
   ```bash
   source ~/.zshrc
   ```

## Prerequisites

- [Oh My Zsh](https://ohmyz.sh/) - Zsh framework
- [fzf](https://github.com/junegunn/fzf) - Fuzzy finder
- [zoxide](https://github.com/ajeetdsouza/zoxide) - Smart cd command
- [Oh My Tmux](https://github.com/gpakosz/.tmux) - Tmux configuration framework

## Customization

Feel free to fork and modify these configs to suit your needs. The configurations are designed to be modular and easy to extend.

## License

MIT License - feel free to use and modify as needed.
