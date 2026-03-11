# 苔寺 Kokedera

*A Zed theme born from moss and silence.*

---

> 古池や　蛙飛び込む　水の音
>
> *The old pond — a frog jumps in, the sound of water.*
> — Matsuo Bashō

---

## The Garden

**Kokedera** (苔寺, *Temple of Moss*) is a dark theme for [Zed](https://zed.dev),
inspired by **Saihō-ji** — the ancient moss temple garden in Kyoto, where over
120 varieties of moss blanket the earth beneath towering cedars and maples.

When you code with Kokedera, you sit in that garden:

- The **editor background** is the deep shade beneath ancient trees
- **Keywords** glow like sunlight catching the brightest moss
- **Strings** carry the warm amber of shōji lanterns at dusk
- **Comments** are weathered stone inscriptions, softened by time
- **Types** stand tall like the dark green cedars
- **Functions** sway like fresh bamboo in a gentle breeze
- **Errors** appear as a distant torii gate — present, but not alarming
- Your **cursor** is a firefly, drifting through the garden at nightfall

## Preview

```
┌──────────────────────────────────────┐
│  ░░░ Deep forest dark ░░░           │
│                                      │
│  fn  garden()  {                     │
│      let moss = "ancient";           │
│      let stones = 108;               │
│      // 静寂 — silence               │
│      temple.illuminate(moss);        │
│  }                                   │
│                                      │
│  ▓ cursor blinks like a firefly     │
└──────────────────────────────────────┘
```

## Installation

### From Zed Extensions (recommended)

1. Open **Zed**
2. Open the command palette: `Cmd+Shift+P` (macOS) / `Ctrl+Shift+P` (Linux)
3. Search for **"zed: extensions"**
4. Search for **"Kokedera"**
5. Click **Install**
6. Open command palette again and search for **"theme selector: toggle"**
7. Select **Kokedera**

### Manual Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/7th-Layer/kokedera-theme-extension-zed.git
   ```

2. Locate your Zed extensions directory:
   - **macOS**: `~/.local/share/zed/extensions/installed/`
   - **Linux**: `~/.local/share/zed/extensions/installed/`

3. Copy or symlink the theme folder:
   ```bash
   ln -s /path/to/kokedera-theme ~/.local/share/zed/extensions/installed/kokedera-theme
   ```

4. Restart Zed and select the theme from the theme selector.

### As a Dev Extension

1. Open Zed
2. Open command palette → **"zed: install dev extension"**
3. Select the `kokedera-theme-extension-zed` folder
4. The theme will be available immediately

## Palette

| Role | Color | Hex |
|------|-------|-----|
| Editor Background | ![#121a11](https://placehold.co/12x12/121a11/121a11) | `#121a11` |
| Surface | ![#151e14](https://placehold.co/12x12/151e14/151e14) | `#151e14` |
| Moss Panel | ![#1a2619](https://placehold.co/12x12/1a2619/1a2619) | `#1a2619` |
| Selection | ![#2a3d26](https://placehold.co/12x12/2a3d26/2a3d26) | `#2a3d26` |
| Stone Border | ![#3a4a35](https://placehold.co/12x12/3a4a35/3a4a35) | `#3a4a35` |
| Text | ![#c8d8b8](https://placehold.co/12x12/c8d8b8/c8d8b8) | `#c8d8b8` |
| Keywords | ![#4ca64c](https://placehold.co/12x12/4ca64c/4ca64c) | `#4ca64c` |
| Strings | ![#d4c88e](https://placehold.co/12x12/d4c88e/d4c88e) | `#d4c88e` |
| Functions | ![#8fbf6f](https://placehold.co/12x12/8fbf6f/8fbf6f) | `#8fbf6f` |
| Types | ![#3d9970](https://placehold.co/12x12/3d9970/3d9970) | `#3d9970` |
| Variables | ![#a3be8c](https://placehold.co/12x12/a3be8c/a3be8c) | `#a3be8c` |
| Numbers | ![#c49a5c](https://placehold.co/12x12/c49a5c/c49a5c) | `#c49a5c` |
| Comments | ![#5a6b50](https://placehold.co/12x12/5a6b50/5a6b50) | `#5a6b50` |
| Cursor | ![#5ae65a](https://placehold.co/12x12/5ae65a/5ae65a) | `#5ae65a` |
| Error | ![#c45a5a](https://placehold.co/12x12/c45a5a/c45a5a) | `#c45a5a` |
| Warning | ![#bfa243](https://placehold.co/12x12/bfa243/bfa243) | `#bfa243` |

## Philosophy

> 侘寂 — **Wabi-sabi**: beauty in imperfection, transience, and incompleteness.

This theme does not shout. It does not demand attention.
It creates a quiet space where code can breathe.

Every color earns its place — no tone overpowers another.
Like the garden itself, the palette grows from a single source:
the endless, patient green of moss.

---

*Step softly. The moss remembers.*

## License

[MIT](LICENSE)
