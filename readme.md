<h1 align="center">
  <img src="https://raw.githubusercontent.com/thang-nm/Flow-Icons/main/logo.png" width="160" alt="Flow Icons"/><br/>
  <a href="https://marketplace.visualstudio.com/items?itemName=thang-nm.flow-icons">Flow Icons</a>
</h1>

<p align="center">
  🌼 A brand new premium icon pack for VSCode
</p>

<p align="center">
  💎 <strong>IMPORTANT</strong> 💎
  <br>
  The extension contains only demo icons.
  <br>
  To download all the icons, you need a license key.
  <br>
  Purchase from the link below:
  <br>
  <br>
  <a target="_blank" href="https://flow-icons.pages.dev">
    <img src="https://img.shields.io/badge/Get_full-Flow_Icons-blue?colorA=363a4f&colorB=c6a0f6&style=for-the-badge">
    &nbsp;
    <img src="https://img.shields.io/badge/dynamic/json?label=Files&colorA=363a4f&colorB=eed49f&style=for-the-badge&url=https%3A%2F%2Fflow-icons.pages.dev%2Fstatistics.json&query=files">
    &nbsp;
    <img src="https://img.shields.io/badge/dynamic/json?label=Folders&colorA=363a4f&colorB=a6da95&style=for-the-badge&url=https%3A%2F%2Fflow-icons.pages.dev%2Fstatistics.json&query=folders">
  </a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/thang-nm/Flow-Icons/main/preview_light.png">
    <img width="640" src="https://raw.githubusercontent.com/thang-nm/Flow-Icons/main/preview.png">
  </picture>
</p>

## ✨ What's New

### `Flow You` Icon Theme

Introducing a whole new color palette made from your colors

(See [Flow You](#flow-you) for more details)

<img width="640" src="https://raw.githubusercontent.com/thang-nm/Flow-Icons/main/you/sequoia_moonlight.png">

### Agents Window Support

To make the icon theme work in the VS Code Agents window, add the following setting to your `settings.json`:

(See [this](https://code.visualstudio.com/docs/copilot/agents/agents-window#_use-vs-code-extensions-in-the-agents-window) for more details)

```json
"extensions.supportAgentsWindow": {
  "thang-nm.flow-icons": true
}
```

## Preview

<p align="center">
  <img width="640" src="https://raw.githubusercontent.com/thang-nm/Flow-Icons/main/freeCodeCamp.png">
</p>

## Packs

See [Toggle icon packs](#toggle-icon-packs) guide.

<p align="center">
  <img width="640" src="https://raw.githubusercontent.com/thang-nm/Flow-Icons/main/packs.png">
</p>

## Alternatives

See [Icon replacements](#icon-replacements) guide.

<p align="center">
  <img width="640" src="https://raw.githubusercontent.com/thang-nm/Flow-Icons/main/alternatives.png">
</p>

## Icons

<p align="center">
  <img width="640" src="https://raw.githubusercontent.com/thang-nm/Flow-Icons/main/icons.png">
</p>

## 💎 Get Premium Icons

To download all icons, you need a license key. You can make a payment [here](https://flow-icons.pages.dev). \
Then, go to the `Extensions > Flow Icons > License Key` and enter your license key. \
You'll then be prompted to download the icons.

## Features

- Supports dark and light themes
- Looks great even on non-Retina displays
- Includes most common file and folder types
- Offers customization options

## Customization

### Settings

Defaults for each setting are shown below.

```jsonc
{
  // Set default folder color
  // Available colors: gray | blue | brown | green | lime | orange | pink | purple | red | sky | teal | yellow
  "flow-icons.folderColor": "gray",

  // Set to `true` to hide folding arrows next to folder icons.
  "flow-icons.hidesExplorerArrows": false,

  // Set to `true` to hide folder icons.
  "flow-icons.hidesExplorerFolders": false,

  // Set to `false` to only use the default folder icon.
  "flow-icons.specificFolders": true,
}
```

To see all available options, open your settings UI and look for `Extensions > Flow Icons`.

### Flow You

<img width="640" src="https://raw.githubusercontent.com/thang-nm/Flow-Icons/main/you/ayu_dark.png">

Icon theme based on your colors. You can customize the colors like the sample below:

```jsonc
"flow-icons.you.colors": {
  // Dark theme colors
  "white": "#bfbdb6",
  "black": "#0d1017",
  "blue": "#59c2ff",
  "brown": "#e6c08a",
  "gray": "#667381",
  "green": "#aad94c",
  "lime": "#c0e76e",
  "orange": "#ff8f40",
  "pink": "#f6adae",
  "purple": "#d2a6ff",
  "red": "#f07178",
  "sky": "#39bae6",
  "teal": "#95e6cb",
  "yellow": "#ffcb8f",
  // "border": "#ffffff", // use the `white`/`black` color, but you can override it.
  "borderOpacity": 0, // hide borders by setting opacity to 0.

  // Light theme colors are auto-generated from dark theme colors,
  // but you can override them in the `light` key.
  "light": {
    // "white": "...",
    // "black": "...",
    // "blue": "...",
    // ...
    "borderOpacity": 0.1, // use borders in the light theme for a better look
  },
}
```

See all sample palettes [here](https://github.com/thang-nm/Flow-Icons/tree/main/you).

### Custom icon associations

Compatible with Material Icon settings, but with a difference: `**` will be treated as `*`.

If you want to remove the icon, set the value to "".

You can see the file and folder names in the preview image or [here](https://flow-icons.pages.dev/icons).

#### File associations

```jsonc
"flow-icons.files.associations": {
  // Add or replace an icon for a file extension
  "*.tss": "typescript",
  // Remove the icon for a file extension
  // (If the extension maps to a language, language icon will be used)
  "*.mdx": "",
  // Add or replace an icon for a specific file name
  "tailwind.css": "tailwindcss",
  // Remove the icon for a specific file name
  // (If the file maps to a language, language icon will be used)
  "package.json": "",

  // In a specific folder
  "src/index.js": "javascript-other", // for a name
  "src/*.index": "javascript-other", // for an extension
},
```

#### Folder associations

```jsonc
"flow-icons.folders.associations": {
  // Add or replace an icon for a folder name
  "store": "resource",
  // Remove the icon for a folder name
  "data": "",

  // In a specific folder
  "src/store": "archive",
}
```

#### Language associations

```jsonc
"flow-icons.languages.associations": {
  // Add or replace an icon for a language
  "languageId": "iconName",
  "json5": "json",
  // Remove the icon for a language
  "jsonc": ""
}
```

### Toggle icon packs

```jsonc
"flow-icons.activeIconPack": {
  "angular": true,
  "bashly": true,
  "nest": false,
  "next": true,
  "roblox": true
},
```

The default value is shown above. For more details about the packs, please see [settings.json](https://github.com/thang-nm/Flow-Icons/blob/main/settings.json).

You can set the value to `false` if you want to disable it. (The `angular` and `nest` packs will conflict if you enable both).

⚠️ Quickly see all available packs [here](https://github.com/thang-nm/Flow-Icons/tree/main?tab=readme-ov-file#toggle-icon-packs).

### Icon replacements

Some icons have alternative versions, which you can use to replace the default ones.

#### File replacements

```jsonc
"flow-icons.files.replacements": {
  // "replace-icon": "with-icon",
  "rust": "rust-alt",
  "kotlin": "kotlin-alt",
},
```

#### Folder replacements

```jsonc
"flow-icons.folders.replacements": {
  // "replace-icon": "with-icon",
  "components": "react-components"
},
```

## Command List

| Command            | Description                             |
| ------------------ | --------------------------------------- |
| **Download Icons** | Download the latest icons.              |
| **Rebuild Icons**  | Rebuild the icons with custom settings. |

## Requesting Icons

To request a new icon, [open an issue](https://github.com/thang-nm/Flow-Icons/issues/new) and describe the icons you need.

<br>

<hr>

<p align="center">
  brought to you by <a href="https://x.com/thang_nm" target="_blank">thang-nm</a>
</p>
