# CraftEngine Item Editor

A Vite + React webapp for building CraftEngine custom Minecraft item configs with a live Minecraft-style tooltip preview and copyable `.yml` export.

## Features

- CraftEngine item identity, material, category, `item_model`, and `custom_model_data` fields.
- Rich MiniMessage item names and lore with hex colors, bold, italic, underline, strikethrough, obfuscated, and `<!i>`.
- Enchantments, tooltip hiding, durability, dyes, trims, equippable data, food data, attributes, block state, and custom component YAML.
- CraftEngine settings such as tags, repairability, fuel, remainders, invulnerability, glow color, equipment, projectiles, and item behaviors.
- Persistent local editing state, copy to clipboard, and `.yml` download.
- Lando Norris-inspired editorial UI with custom controls, smooth scrolling, and live preview.

## Local Development

```bash
npm install
npm run dev
```

## Production Build

```bash
npm run build
```

The static build is emitted to `dist/`.

## Vercel

Import this folder as a Vercel project. Vercel should detect Vite automatically.

- Framework preset: `Vite`
- Build command: `npm run build`
- Output directory: `dist`
- Install command: `npm install`

The app is fully client-side and does not need environment variables.
