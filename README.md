# devbox-vscode-template

[devbox](https://www.jetify.com/docs/devbox/) and [direnv](https://direnv.net/), wired into VS Code

## Prerequisites

```sh
curl -fsSL https://get.jetify.com/devbox | bash
brew install direnv
```

## Repo Setup

```sh
REPO=<your-repo>
gh repo create "$REPO" --template jcosentino11/devbox-vscode-template --private --clone
cd "$REPO"
direnv allow
code .
```

> Reload the window afterward.

## Usage

Opening the project loads devbox's isolated env automatically.

```sh
code .
```
