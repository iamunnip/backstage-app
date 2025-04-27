# Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)

# Prerequisites

- A Linux distribution (here I'm using Arch Linux)
- Dependency packages like `make`, `build-essential`, `curl`, `wget`
- Node.js active LTS release, install using `nvm`
    ```
    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
    \. "$HOME/.nvm/nvm.sh"
    nvm install 20
    node -v
    nvm current
    ```
- Yarn installation
    ```
    corepack enable yarn
    yarn set version 4.4.1
    yarn -v
    ```
- Docker installation
- Git installation

# Installation
Install Backstage

```sh
npx @backstage/create-app@latest

or

npx @backstage/create-app@0.6.1
```

This is your newly scaffolded Backstage App, Good Luck!

To start the app, run:

```sh
yarn install
yarn start
```
