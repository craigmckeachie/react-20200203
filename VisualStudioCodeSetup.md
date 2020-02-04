# Appendix A2: Visual Studio Code Extensions

## Extensions

### Install the following extensions:

1.  **Click** the **link** below.
    - [Prettier- Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode&ssr=false#overview)
    - [HTML to JSX](https://marketplace.visualstudio.com/items?itemName=riazxrazor.html-to-jsx)
    - [Jest Snippets](https://marketplace.visualstudio.com/items?itemName=andys8.jest-snippets)
    - [Color Theme: Cobalt2](https://marketplace.visualstudio.com/items?itemName=wesbos.theme-cobalt2)
    - [File Icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
1.  **Click** the **Install** button.

## Configure settings

1. On the bottom left of VS Code > click the `Gear Icon`
2. Choose `Command Palette..`
3. Type `open settings`
4. Choose `Open Settings.JSON`
5. Paste the settings below into the file.

If you have existing `USER SETTINGS` you will want to **add** the following settings below your current settings. Otherwise, you can replace the contents of the file with the JSON below.

`settings.json`

```json
{
  "files.autoSave": "afterDelay",
  "editor.fontFamily": "Fira Code iScript, Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.multiCursorModifier": "alt",
  "editor.formatOnSave": true,
  "workbench.iconTheme": "material-icon-theme",
  "emmet.includeLanguages": {
    "typescript": "html"
  }
}
```

6. Create a `code` directory (as a sibling to the `docs` directory) where you will write code during the course and copy [prettier.config.js](./prettier.config.js) into it.

## Install a font for programming (optional)

If you are interested in trying a new font designed for programming.

1. Install the free [FiraCodeiScript](https://github.com/kencrocken/FiraCodeiScript) font on your system.

- [How to Install Fonts on Windows 10](https://www.groovypost.com/howto/install-fonts-windows-10/)
- [How to Install Fonts on Mac](https://www.dafont.com/faq.php#mac)

2. Close and reopen VS Code to see the new font.

## Reference

- [VS Code ReactJS Tutorial](https://code.visualstudio.com/docs/nodejs/reactjs-tutorial)

#### Other Extensions (not required)

- [React & JS Snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets) OR [Simple React Snippets](https://marketplace.visualstudio.com/items?itemName=burkeholland.simple-react-snippets)
- [React Documentation Extension](https://marketplace.visualstudio.com/items?itemName=avraammavridis.vsc-react-documentation)
