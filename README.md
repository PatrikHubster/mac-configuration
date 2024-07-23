# MacOS configuration

## Installation

Install brew via the following command ...

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Afterwards run the following command ...

```bash
brew bundle --file=./Brewfile
```

## Docker

Docker is used in the style described in this [Medium article](https://medium.com/@damasamirulkarim/how-i-use-docker-without-docker-desktop-on-macos-df251dae3b81).

## Automatic updates

This documentation is based on this [Medium article](https://truptivbhatt.medium.com/how-to-run-your-shell-script-automatically-after-logging-to-mac-da789bb78d21). In the Automator it is also possible to open a automation via `Files`. To adopt the existing `Development environment setup` app use this option. Use the Phase 2 of this Medium article to import the `Development environment setup` script of this repository:

1. Go to System preferences.
2. Search for login items.
3. Select the user for which you want to run script automatically.
4. Click on (+) Plus sign from the second pane. (If you hover on it , you can see “Add an item to the login item list.”) One popup will be opened.
5. Browse to the path of the application (script) which you have created using above steps and click on Add button. Your Script is added under the login item list box.