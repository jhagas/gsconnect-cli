# GNOME Gsconnect Extension Send Script
Did you use [GNOME](https://www.gnome.org/) and its [KDE Connect](https://kdeconnect.kde.org/) Implementation, [Gsconnect](https://extensions.gnome.org/extension/1319/gsconnect/)? But you want to transfer file to your android via terminal file manager (for example [nnn](https://github.com/jarun/nnn)), or even another GUI File Manager (in case you don't like nautilus).
This is the answer for your need..

## Dependencies
This script is using `dmenu` and `readlink`.

**THIS SCRIPT WILL ONLY WORKS IN GNOME DE!!**
if you're not using GNOME,
You may consider using [KDE Connect](https://kdeconnect.kde.org/) instead of Gsconnect

## :penguin: Linux Installation
For installation, just copy these commands into your terminal and press ENTER
```bash
sudo curl -sL https://github.com/jhagas/gsconnect-cli/raw/main/gsconnect -o /usr/local/bin/gsconnect
sudo chmod +x /usr/local/bin/gsconnect
```

## USAGE

`gsconnect <OPTION> <path|filename>`

**List of option available**
|OPTION|to
|---|---|
|-h or --help|To display help message|
