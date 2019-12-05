# Adventure Code

A sober dark color theme based on the color palette of the popular Cartoon Network show Adventure Time. Based on the 

### Tweaks & theming

If you want to play around with new colors, use the setting
`workbench.colorCustomizations` to customize the currently selected theme. For
example, you can add this snippet in your "settings.json" file:

```json
"workbench.colorCustomizations": {
  "tab.activeBackground": "#282c34",
  "activityBar.background": "#282c34",
  "sideBar.background": "#282c34"
}
```

or use the setting `editor.tokenColorCustomizations`

```json
"editor.tokenColorCustomizations": {
  "[One Dark Pro]": {
    "textMateRules": [
      {
        "scope": ["source.python"],
        "settings": {
          "foreground": "#e06c75"
        }
      }
    ]
  }
}
```

Please check the official documentation,
[Theme Color Reference](https://code.visualstudio.com/docs/getstarted/theme-color-reference) and
[Theme Color](https://code.visualstudio.com/docs/getstarted/themes), for more helpful information.

![setting.json](https://camo.githubusercontent.com/e3931303eec6fbfb79c424cd30ca2d50f49c8416/68747470733a2f2f7773342e73696e61696d672e636e2f6c617267652f303036744e6252776779316676776a6f716e6274676a33316b773130317768762e6a7067)

![custom](https://camo.githubusercontent.com/179963baf6ded2934ec5dba08a65f61ca8d0b34f/68747470733a2f2f7773332e73696e61696d672e636e2f6c617267652f303036744e6252776779316676776a70776e7137626a33307175313477337a722e6a7067)

[More info](https://code.visualstudio.com/updates/v1_15#_user-definable-syntax-highlighting-colors)
