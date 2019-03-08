# A Simple Boilerplate

A simple boilerplate for vscode to work with parceljs and debugging with chrome.

install the build tools:

```sh
$ npm run install-tools
```

This command will install parceljs and eslint.

To start the example, simply run:

```sh
$ npm run start
```

## gitignore global

Force git to globally ignore nodejs build files, copy the gitignore_global file to your home directory and rename it to .gitignore_global.

Then execute the following command:

```sh
$ git config --global core.excludesfile ~/.gitignore_global
```

From now on your node_modules, npm, ignore files and directories are not included in any of your repositories.
