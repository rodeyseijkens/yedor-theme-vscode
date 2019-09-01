<h1 align="center">
    Yedor Theme
</h1>

## Installation

1. Open the **Extensions** sidebar in VS Code
2. Search for `Yedor`
3. Click **Install**
4. Open the **Command Palette** with `Ctrl+Shift+P` or `⇧⌘P`
5. Select **Preferences: Color Theme** and choose **Yedor**
6. Enjoy! 🌅 Also, check out some of the personalization options below...

## Personalization

This theme is the byproduct of some very opinionated changes to both <a href="https://marketplace.visualstudio.com/items?itemName=jolaleye.horizon-theme-vscode">Horizon Theme</a>.

_For more info on theming, visit the [Theme Authoring Guide](https://code.visualstudio.com/api/extension-capabilities/theming) and [Theme Color Reference](https://code.visualstudio.com/api/references/theme-color)._

## Recommended Fonts, Extensions & Settings

I am a big fan of fonts that support ligatures. I highly recommend the following fonts:

- <a href="https://dank.sh/">Dank Mono (£40)</a>
- <a href="https://github.com/tonsky/FiraCode">Fira Code (Free)</a>

> Note: Ensure you enable font ligatures by adding `"editor.fontLigatures": true,` to your `settings.json` file.

I also highly recommended two particular extensions to help augment this theme even further:

- <a href="https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments">Better Comments</a>
- <a href="https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2">Bracket Pair Colorizer 2</a>

Download these extensions and add the following settings to your `settings.json` file.

### Better Comments

<img src="https://i.imgur.com/pPUkIlI.png" alt="Better Comments preview">

```json
"better-comments.tags": [
    {
      "tag": "!",
      "color": "#2E302E",
      "strikethrough": false,
      "backgroundColor": "#E95678"
    },
    {
      "tag": "?",
      "color": "#2E302E",
      "strikethrough": false,
      "backgroundColor": "#B877DB"
    },
    {
      "tag": "//",
      "color": "#474747",
      "strikethrough": true,
      "backgroundColor": "transparent"
    },
    {
      "tag": "todo",
      "color": "#FAB795",
      "strikethrough": false,
      "backgroundColor": "#2E302E"
    },
    {
      "tag": "*",
      "color": "#FDF0ED",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    {
      "tag": "#",
      "color": "#FDF0ED",
      "strikethrough": false,
      "backgroundColor": "#2E302E"
    },
    {
      "tag": "_",
      "color": "#2E302E",
      "strikethrough": false,
      "backgroundColor": "#FDF0ED"
    }
  ],
```

### Bracket Pair Colorizer 2

<img src="https://i.imgur.com/GprIokQ.png" alt="Bracket Pair Colorizer 2 preview">

```json
"bracket-pair-colorizer-2.colors": ["#FAC29A", "#B877DB", "#25B2BC"],
```

[MIT](LICENSE) © [Rodey Seijkens](https://github.com/rodeyseijkens)
