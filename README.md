# Tittle - Dotfile Manager

Tittle tracks your dotfiles under version control and supports fine-grained
user/machine-specific configuration.

## Quick Start
```
> tittle track ~/.config/i3
INFO: tracking /home/enricozb/.config/i3 under i3
> tittle repo git@github.com:enricozb/dotfiles
> tittle push
```

## Install
Currently the easiest way to install tittle is through `cargo`:
```
cargo install tittle
```

## Documentation
  - [commands](doc/commands.asciidoc): for info on the commands that tittle accepts.
  - [config](doc/config.asciidoc): for the tittle config specification.
  - [templates](doc/templates.asciidoc): for how to use templates and variables.

## Terminology
Throughout the codebase and this document the terms *remote* and *local* appear often.
*Remote* refers to files that are under the `$XDG_CONFIG_HOME/tittle` directory. *Local*
files are those on the user's filesystem currently being used as configs.

## To do
See [todo](todo.md).

## Why?
No idea.
