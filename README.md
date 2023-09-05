# PAURA

A simple helper for managing AUR packages.

## Description

This helper is definitely not the best, there are many others out there, more
famous and with a lot more features to offer.

What this script excels at is simplicity. A hundred lines of Bash to
install, update and remove AUR packages on any Arch-based distribution.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Installation

With `curl`:

```shell
curl -o $HOME/.local/bin/paura https://raw.githubusercontent.com/marcoplaitano/paura/main/paura
```

With `wget`:

```shell
wget -O $HOME/.local/bin/paura https://raw.githubusercontent.com/marcoplaitano/paura/main/paura
```

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Usage

**Installing** or **updating** a package:

```shell
paura pfetch
# or
paura https://aur.archlinux.org/pfetch
```

**Removing** a package:

```shell
paura -r pfetch
```

**Listing** all installed packages:

```shell
paura -l
```

**Updating all** installed packages:

```shell
paura -u
```

### Options Summary

| Option                | Description                               |
|-----------------------|-------------------------------------------|
| -h, --help            | Show help guide and exit.                 |
| **PKG**               | Install or update package named **PKG**.  |
| -l, --list            | List all installed packages.              |
| -r, --remove **PKG**  | Remove package named **PKG**.             |
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
