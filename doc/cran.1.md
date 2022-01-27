# NAME

cran - an easy package manager for R written in bash

# SYNOPSIS

cran [OPTION] [ARGS]...

# Description

version, v, -v, ver

> Print version and exit

install, i, -i, ins

> Install packages

download, d, -d, dow

> Download package source

remove, r, -r, rm

> Remove/uninstall packages

list, l, -l, ls

> List installed packages

help, h, -h, hlp

> Print all commands

update, u, -u, upt

> Update all packages

updates, U, -U, upd

> Print all updatable packages

depends, D, -D, dep

> Print dependencies in cranfile

# CONFIG FILE

By default the config file is in `~/.config/cran.conf` it gets created automatically on first launch.

Configuration variables are:
- `repos` -- This is an R vector of your mirrors, the first value should be a . (if used as an R vector) and all of your mirrors should be separated by spaces
- `root_required` -- This value controls if cran requires root access to run
- `r_interpreter` -- The path to your R interpreter
- `r_flags` -- The flags passed to the R interpreter when running a command, I'd suggest leaving it as-is

