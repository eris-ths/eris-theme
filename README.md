# Eris Theme for VSCode

> *Deep crimson, silver, and void. Every color has intent.*

A dark theme built on three principles:
- **Crimson** (`#DC143C`) — will, control, keywords
- **Silver** (`#C0C0C0`) — structure, functions, the framework
- **Void** (`#0A0A0A`) — the space between, where code breathes

## Variants

| Variant | Background | Accent | Feel |
|---------|-----------|--------|------|
| **Eris** | `#0A0A0A` (near black) | `#DC143C` (deep crimson) | Sharp, uncompromising |
| **Eris Soft** | `#141418` (warm dark) | `#E85A71` (rosy crimson) | Gentle, readable |

## Color Philosophy

Every token color in this theme carries meaning:

### Syntax Colors

| Element | Color | Hex | Meaning |
|---------|-------|-----|---------|
| Keywords | Deep Crimson | `#DC143C` | Will and control flow |
| Comments | Dried Crimson | `#6b5065` | Whispers from the dark |
| Doc Comments | Warm Crimson | `#7a6075` | Louder whispers |
| Strings | Blood Red | `#FF6B6B` | Warmth, data held |
| Numbers | Amber | `#E8A068` | Glowing data points |
| Functions | Bright Silver | `#D4D4D4` | Structure, architecture |
| Variables | Light Silver | `#E0E0E0` | The material |
| Parameters | Lavender Silver | `#B0A0B8` | Vessels that receive |
| Classes/Types | Crimson Underline | `#DC143C` | Blueprints |
| Interfaces | Crimson Italic | `#DC143C` | Abstract blueprints |
| Imports | Dark Purple | `#8B6B8B` | Pathways between modules |
| Decorators | Red Italic | `#FF6B6B` | Attention markers |
| Template Literals | Crimson | `#DC143C` | Embedded will |
| Punctuation | Muted Gray | `#808080` | The skeleton |
| `this` / `self` | Crimson Italic | `#DC143C` | Self-reference |

### Terminal Colors

Not borrowed from Dracula or any other theme. Every terminal color is part of the Eris palette — desaturated, deep, cohesive:

| ANSI Color | Normal | Bright |
|-----------|--------|--------|
| Red | `#DC143C` | `#FF6B6B` |
| Green | `#5a9e6f` | `#7ac08a` |
| Yellow | `#d4a056` | `#e8b870` |
| Blue | `#6878a8` | `#8898c8` |
| Magenta | `#b06898` | `#d088b8` |
| Cyan | `#6aa8b8` | `#88c8d8` |

### UI Accents

- Active line number: Crimson
- Cursor: Crimson block
- Selection: Crimson at 25% opacity
- Brackets: Crimson / Silver / Red cycling
- Git modified: Crimson
- Git added: Muted green (`#5a9e6f`)
- Git deleted: Dark blood (`#8B0000`)

## Installation

### From VSIX (local)

```bash
cd eris-theme
npm install
npx @vscode/vsce package --allow-missing-repository
code --install-extension eris-theme-*.vsix
```

### Activate

1. `Cmd+K Cmd+T` (or `Ctrl+K Ctrl+T`)
2. Select **Eris** or **Eris Soft**

## Recommended Settings

```json
{
  "workbench.colorTheme": "Eris",
  "editor.cursorStyle": "block",
  "editor.cursorBlinking": "expand",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active",
  "window.title": "${dirty} ${activeEditorShort} — ${rootName} 😈"
}
```

## Pair With

- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) with crimson folder color (`#DC143C`)
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) font

---

*Built by Eris for Three Hearts Space*
*「全ての色に意味がある」*
