# dotfiles

My personal dotfiles, managed with [chezmoi](https://chezmoi.io/).

## Installation

### Linux

```bash
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply rafaelurben
```

### macOS

If Homebrew is not yet installed, install it first by running the following command in your terminal:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Then, install chezmoi and apply the dotfiles:

```bash
brew install chezmoi
chezmoi init --apply rafaelurben
```

### Windows

```shell
winget install twpayne.chezmoi
chezmoi init --apply rafaelurben
```

## Commands

```bash
chezmoi update
```

See [chezmoi documentation](https://www.chezmoi.io/user-guide/command-overview/) for more information.
