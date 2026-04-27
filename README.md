# PAURA

A simple helper for managing AUR packages.

## Description

This helper is definitely not the best, there are many others out there, more
famous and with a lot more features to offer.

What this script excels at is simplicity. A hundred lines of Bash to
install, update and remove AUR packages on any Arch-based distribution.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Installation

Download and give executable permissions:

```shell
curl -o $HOME/.local/bin/paura.sh https://raw.githubusercontent.com/marcoplaitano/paura/main/paura.sh
chmod +x $HOME/.local/bin/paura.sh
```

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Usage

**Installing** or **updating** a package:

```shell
paura.sh pfetch
# or
paura.sh https://aur.archlinux.org/pfetch
```

**Removing** a package:

```shell
paura.sh -r pfetch
```

**Listing** all installed packages:

```shell
paura.sh -l
```

**Updating all** installed packages:

```shell
paura.sh -u
```

**Search** for a package:

```shell
paura.sh -s pfetch
```

### Options Summary

| Option                | Description                               |
|-----------------------|-------------------------------------------|
| -h, --help            | Show help guide and exit.                 |
| **PKG**               | Install or update package named **PKG**.  |
| -l, --list            | List all installed packages.              |
| -r, --remove **PKG**  | Remove package named **PKG**.             |
| -s, --search **PKG**  | Search package named **PKG**.             |
| -u, --update          | Update all installed packages.            |

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Author

Marco Plaitano

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## License

Distributed under the [MIT] license.

<!-- Links -->

[MIT]:
LICENSE
"Repository file"
