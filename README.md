# dotfiles

My personal dotfiles.

## Installation

### Linux

```bash
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply rafaelurben
```

### macOS

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install chezmoi
chezmoi init --apply rafaelurben
```

## Update

```bash
chezmoi update
```
