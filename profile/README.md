<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/yof-logo-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/yof-logo-light.svg">
    <img alt="yof" src="assets/yof-logo-light.svg" width="220">
  </picture>
</p>

<p align="center"><strong>Security checks for apps you build with AI</strong></p>

<p align="center">Catch leaked keys, open databases and risky packages before you ship. Free and open source.</p>

yof looks for the mistakes AI builders tend to leave behind: secret keys in the code, packages that don't exist or imitate popular ones, and routes where one user can read another user's data. Everything here runs on your own machine, needs no account, and is free to use.

## What's here

| Repository | What it is |
| --- | --- |
| [yof](https://github.com/yof-dev/yof) | The command-line check (`npx @yof/cli check`), `yof attack` for your own running app, and the GitHub Action that runs both on every push and pull request |
| [yof-vscode](https://github.com/yof-dev/yof-vscode) | The extension for VS Code, Cursor and Windsurf: findings in Problems when you save, with a fix prompt for your AI assistant |
| [yof-jetbrains](https://github.com/yof-dev/yof-jetbrains) | The plugin for IntelliJ IDEA, WebStorm, PyCharm and the other JetBrains IDEs |
| [yof-demo](https://github.com/yof-dev/yof-demo) | A tiny notes app with five planted problems, so you can watch yof find them. Insecure on purpose: never deploy it |

## Try it in 30 seconds

```sh
npx @yof/cli check
```

Node 20 or newer. Nothing to configure, and your code never leaves your machine.

## More

- Website: [yof.io](https://yof.io)
- How yof does against known test apps: [yof.io/benchmark](https://yof.io/benchmark)
- Found a security problem in yof itself? Write to [security@yof.io](mailto:security@yof.io). Please don't open a public issue for it.
- Licence: Apache-2.0, in every repository.

yof is powered by sōtem.
