# How to use

Install brew via the following command ...

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Afterwards run the following command ...

```bash
brew bundle --file=./Brewfile
```

Make the `brew-update.sh` executable ...

```bash
chmod +x ./brew-update.sh
```

Register the script to `chezmoi` ...

```bash
chezmoi add "brew update" "bash ~/Code/mac-configuration/brew-update.sh" --time 10:00
```