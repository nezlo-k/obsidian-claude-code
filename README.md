# Claude Code Theme for Obsidian

A terminal-inspired theme based on the [Claude Code CLI](https://docs.anthropic.com/en/docs/claude-code) aesthetic. Pure black background, cool grays, minimal accents, monospace throughout.

## Features

- **Pure black background** (#0a0a0a) — true terminal feel
- **Monospace everywhere** — SF Mono / JetBrains Mono / system fallbacks
- **Minimal syntax highlighting** — formatting markers fade into background
- **No distractions** — no colored headers, no fancy decorations
- **Tight spacing** — compact, terminal-like line heights
- **iOS compatible** — falls back to SF Mono on Apple devices

## Screenshots

*Coming soon*

## Installation

### Manual
1. Download `theme.css` and `manifest.json`
2. Create folder: `YourVault/.obsidian/themes/Claude Code/`
3. Place both files in that folder
4. Settings → Appearance → Themes → Select "Claude Code"

### Obsidian Community Themes
*Not yet published*

## Customization

Key CSS variables you can override in a snippet:

```css
.theme-dark {
  /* Backgrounds */
  --background-primary: #0a0a0a;
  --background-secondary: #141414;
  
  /* Text */
  --text-normal: #e0e0e0;
  --text-muted: #888888;
  --text-faint: #484848;
  
  /* Accents */
  --text-accent: #e0e0e0;
  --interactive-accent: #e0e0e0;
  
  /* Code colors */
  --code-keyword: #7ee787;
  --code-string: #a5d6ff;
}
```

## Recommended Fonts

For the full experience, install:
- [SF Mono](https://developer.apple.com/fonts/) (macOS/iOS built-in)
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) (free, with ligatures)
- [Inter](https://rsms.me/inter/) (optional, for UI elements)

## License

MIT — do whatever you want with it.

## Credits

Inspired by [Claude Code CLI](https://docs.anthropic.com/en/docs/claude-code) by Anthropic.

Built by [Nezlo K](https://nezlok.com) with help from Claude.
