```text
   ___     _
  / __|  _| |__  ___ _ _ _ __ _ _ ___ ______ ___
 | (_| || | '_ \/ -_) '_| '_ \ '_/ -_|_-<_-</ _ \
  \___\_, |_.__/\___|_| | .__/_| \___/__/__/\___/
      |__/              |_|
```

> **The system is noisy. Your editor shouldn't be.**

[![Cyberpresso Theme Preview](https://i.ibb.co/wNfQzZkm/image.png)](#)

## // THE PHILOSOPHY

We stare into the abyss for hours. The abyss shouldn't actively fight back. **Cyberpresso** is a precisely engineered Base16 color scheme designed for prolonged immersion in the syntax.

It rejects the aggressive neon overkill of typical "cyberpunk" themes while avoiding the dullness of washed-out pastels. Instead, it anchors on a deep, obsidian calm (`#12141A`) to drastically reduce cognitive load and visual fatigue. When the code needs to speak, it speaks with surgical, high-contrast accents—highlighting only the anomalies, the logic, and the critical pathways. 

Signal over noise. Always.

## // TECHNICAL SPECIFICATION : BASE16

Built on the Base16 architecture for universal compatibility. No bloated custom configs—just raw hexadecimal values mapping strictly to structural syntax.

| Variable | HEX | Purpose |
| :--- | :--- | :--- |
| **base00** | `#12141a` | Background (The Void) |
| **base01** | `#1c1f26` | Lighter Background (Status bar/Line numbers) |
| **base02** | `#2a2e38` | Selection Background |
| **base03** | `#3e4552` | Comments, Invisibles |
| **base04** | `#777777` | Dark Foreground (Status bars) |
| **base05** | `#a4a8ae` | Default Foreground, Caret, Delimiters |
| **base06** | `#cccccc` | Light Foreground |
| **base07** | `#d9dcdf` | Lightest Foreground |
| **base08** | `#c95a5a` | Variables, XML Tags, Errors |
| **base09** | `#e37349` | Integers, Boolean, Constants |
| **base0A** | `#e6ae5c` | Classes, Search Highlight |
| **base0B** | `#8ba563` | Strings, Inherited Class |
| **base0C** | `#507b9e` | Support, Regular Expressions |
| **base0D** | `#5a86a8` | Functions, Methods, Attribute IDs |
| **base0E** | `#8a719c` | Keywords, Storage, Selector |
| **base0F** | `#a3624c` | Deprecated, Opening/Closing Embedded Tag |

## // DEPLOYMENT : INSTALLATION

### 01. Visual Studio Code

No extension marketplace telemetry needed. If you want raw control, inject this straight into your local `settings.json` to overwrite the default grid.

```json
{
  "workbench.colorCustomizations": {
    "[Your Current Theme]": {
      "editor.background": "#12141a",
      "editor.foreground": "#a4a8ae",
      "editor.selectionBackground": "#2a2e38",
      "editor.lineHighlightBackground": "#1c1f26",
      "editorCursor.foreground": "#a4a8ae",
      "editorWhitespace.foreground": "#3e4552",
      "terminal.background": "#12141a",
      "terminal.foreground": "#a4a8ae",
      "terminalCursor.foreground": "#a4a8ae",
      "terminal.ansiBlack": "#12141a",
      "terminal.ansiRed": "#c95a5a",
      "terminal.ansiGreen": "#8ba563",
      "terminal.ansiYellow": "#e6ae5c",
      "terminal.ansiBlue": "#5a86a8",
      "terminal.ansiMagenta": "#8a719c",
      "terminal.ansiCyan": "#507b9e",
      "terminal.ansiWhite": "#a4a8ae"
    }
  }
}
```
*(Alternatively, use a Base16 theme extension and compile the YAML directly).*

### 02. The Base16 Standard (Global Shells & Editors)

Cyberpresso doesn't discriminate. It's built on the universal [Base16](https://github.com/chriskempson/base16) architecture.

Whether you're compiling in `Vim`, hacking in `Emacs`, navigating `tmux`, or configuring `Alacritty`, you can compile Cyberpresso for your environment using any standard Base16 builder.

1. Clone this repository into your chosen Base16 builder.
2. Run the build script to generate the template for your editor.
3. Reload your environment.

> *"Information is power. But like all power, there are those who want to keep it for themselves."*
> — **Aaron Swartz**

---
**Copyleft** 🄯 The Code belongs to the open network.
