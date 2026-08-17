# devbox-project-vscode-template

Template for new vscode projects that uses [devbox](https://www.jetify.com/docs/devbox/) for nix-based dependency management.

## One-time setup

Install the following if not already on your machine:

* [devbox](https://www.jetify.com/docs/devbox/)
* [direnv](https://direnv.net/)
* vscode extensions from `.vscode/extensions.json`

# Usage

1) Open your project in vscode
2) `direnv allow` to load devbox's env into your shell, tasks, and the extension host

## Helpful Docs

* https://www.jetify.com/docs/devbox/quickstart/
* https://www.jetify.com/docs/devbox/ide_configuration/direnv/
