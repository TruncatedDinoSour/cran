# This repository has been migrated to the self-hosted ari-web Forgejo instance: <https://git.ari.lt/ari/cran>
# Cran

> An easy R package manager written in bash

# Requirements

- R -- https://www.r-project.org/
- Bash -- https://www.gnu.org/software/bash/

# Installation

## Manual

```bash
sudo install -Dm0644 doc/cran.1 /usr/share/man/man1/cran.1
sudo mandb -qf /usr/share/man/man1/cran.1
sudo install -Dm755 cran /usr/local/bin
```

## Packages

- Linux
  - Gentoo linux: [dev-util/cran::dinolay](https://ari-web.xyz/gentooatom/dev-util/cran)

# Configuration

Just edit `~/.config/cran.conf` file, all documentation
in the `man` page.
