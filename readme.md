<h1 align="center">
  <img src="https://raw.githubusercontent.com/thang-nm/Flow-Icons/main/logo.png" width="160" alt="Flow Icons"/><br/>
  <a href="https://marketplace.visualstudio.com/items?itemName=thang-nm.flow-icons">Flow Icons</a>
</h1>

<p align="center">
  A whole new icon pack for VSCode
</p>

<p align="center">
  ⚠️ IMPORTANT: to download all the icons, you need a license key.
  <br>
  Purchase from the link below:
  <br>
  <br>
  <a target="_blank" href="https://flow-icons.pages.dev">
    <img src="https://img.shields.io/badge/Get_full-Flow_Icons-blue?colorA=363a4f&colorB=c4b5fd&style=for-the-badge">
  </a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/thang-nm/Flow-Icons/main/preview_light.png">
    <img width="640" src="https://raw.githubusercontent.com/thang-nm/Flow-Icons/main/preview.png">
  </picture>
</p>

## Preview

<br />

<p align="center">
  <img width="640" src="https://raw.githubusercontent.com/thang-nm/Flow-Icons/main/icons.png">
</p>

## 💎 Get Premium Icons

To download all icons, you need a license key. You can make a payment [here](https://flow-icons.pages.dev). \
Then, go to the `Extensions > Flow Icons > License Key` and enter your license key. \
You'll then be prompted to download the icons.

## Features

- Supports dark, light, and dim themes
- Looks great even on non-Retina displays
- Includes most common file and folder types
- Offers customization options

## Customization

### Settings

Defaults for each setting are shown below.

```jsonc
{
  // Set default folder color
  // Available colors: red | orange | yellow | green | blue | pink | purple | teal | gray
  "flow-icons.folderColor": "gray",

  // Set to `true` to hide folding arrows next to folder icons.
  "flow-icons.hidesExplorerArrows": false,

  // Set to `true` to hide folder icons.
  "flow-icons.hidesExplorerFolders": false,

  // Set to `false` to only use the default folder icon.
  "flow-icons.specificFolders": true
}
```

To see all available options, open your settings UI and look for `Extensions > Flow Icons`.

### Custom icon associations

Compatible with Material Icon settings, but with a difference: `**` will be treated as `*`.

If you want to remove the icon, set the value to "".

You can see the file and folder names in the preview image or [here](https://flow-icons.pages.dev/icons).

#### File associations

```jsonc
"flow-icons.files.associations": {
  // Add an icon for a file extension
  "*.tss": "typescript",
  // Remove the icon for a file extension
  // (If the extension maps to a language, language icon will be used)
  "*.mdx": "",
  // Replace the icon for a file extension
  "*.ts": "video",
  // Add an icon for a specific file name
  "tailwind.css": "tailwindcss",
  // Remove the icon for a specific file name
  "package.json": "",
  // Replace the icon for a specific file name
  "changelog.md": "markdown"
},
```

#### Folder associations

```jsonc
"flow-icons.folders.associations": {
  // Add an icon for a folder name
  "store": "resource",
  // Remove the icon for a folder name
  "data": "",
  // Replace the icon for a folder name
  "storage": "database"
}
```

## Requesting Icons

To request a new icon, [open an issue](https://github.com/thang-nm/Flow-Icons/issues/new) and describe the icons you need.

<br>

<hr>

<p align="center">
  brought to you by <a href="https://x.com/thang_nm" target="_blank">thang-nm</a>
</p>
