# cyder-website
Website for Cyder.

## requirements

Before commiting this project, you need to install:

- [nvm](https://github.com/creationix/nvm)
- [nodejs v7.1.0](https://github.com/nodejs/node)
- [yarn](https://github.com/yarnpkg/yarn)
- [editorconfig plugin](http://editorconfig.org/#download)
- [eslint integration](http://eslint.org/docs/user-guide/integrations#editors)

### install nvm

```sh
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.32.1/install.sh | bash
```

If you are using zsh just change `bash` with `zsh`.

Add the source line below to your profile(`~/.bash_profile`, `~/.zshrc`, `~/.profile`, or `~/.bashrc`).

```sh
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh" # This loads nvm
```

### install nodejs v7.1.0

```sh
nvm install v7.1.0
nvm use v7.1.0 --global
```

### install yarn

```sh
npm i -g yarn
```

### install editorconfig plugin

[Here](http://editorconfig.org/#download) you can find a plugin for the editor you are using.

### install eslint integration

[Here](http://eslint.org/docs/user-guide/integrations#editors) you can find a integration for the editor you are using.

## setup

1. Fork the repo: [https://github.com/cyder-akashi/cyder-website](https://github.com/cyder-akashi/cyder-website)
2. Run the following commands:

```sh
git clone YOUR_TOPICS_REPO_URL
cd cyder-website
yarn
```

## availabel scripts

In the project directory you can run:

### `yarn run dev`

Run the app for development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `yarn run build`

Builds the app for production to the `.next` folder.

### `yarn run build`

Runs the app in the production mode.
Open http://localhost:3000 to view it in the browser.

## author

[Mori-Atsushi](https://github.com/Mori-Atsushi)
