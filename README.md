# Ansible Craft CLI
Install [Craft CLI](https://github.com/rsanchez/craft-cli) globally.

## Installation
Clone this repository inside your ```roles``` directory.

## Usage
Installs ```craft``` to ```/usr/local/bin```

## Role Variables
```
---
# defaults to /usr/local/bin
craft_cli_install_path: /usr/local/bin

# defaults to latest version
craft_cli_version: ~
```