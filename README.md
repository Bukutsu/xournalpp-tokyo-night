# Tokyo Night for Xournal++

Tokyo Night pen palettes for [Xournal++](https://xournalpp.github.io/), faithful to
[enkia's Tokyo Night](https://github.com/tokyo-night/tokyo-night-vscode-theme)
VS Code theme (default **Night** variant, `#1a1b26` + the README color table).

Three palettes, one per paper situation:

| File | Use when | Character |
| --- | --- | --- |
| `tokyo-night.gpl` | Dark paper (`#1a1b26`) | Full glow. Accents hit 6.5–14.5:1 on dark. Falls apart on white (1.2–2.6:1). |
| `tokyo-night-light.gpl` | Light paper (`#e6e7ed`) | Faithful Light-variant inks, dark on light. |
| `tokyo-night-mix.gpl` | Mixed / daily driver | Per-hue pick of whichever rendition reads on more papers. Muted on dark, strong on light. |

No single palette glows on dark paper *and* reads on white — contrast is relative
to the paper, so bright-on-dark inks are always weak-on-light. The Mix guarantees
readability everywhere (mid-grey paper defeats every chromatic ink, so it is excluded):
Grey 3.4, Yellow 3.1, Orange/Cyan 2.8, Red/Teal/Blue 2.5, Green 2.3, Magenta 2.0
(worst-case across white/light/dark/black; 3:1+ is pen-safe). Its two extremes pair up
like default's Black/White: **Ink Dark** for light papers, **Ink Light** for dark ones.

## Install

Copy the `.gpl` files into the `palettes` folder inside your Xournal++ config folder
(`~/.config/xournalpp/palettes/` on Linux), restart Xournal++, then pick the palette
under `Edit → Preferences → Palette`.

Tip: match the page to the palette via `Journal → Configure Page Template` —
background `#1a1b26` for Night, `#e6e7ed` for Light.

## Palettes

### Tokyo Night (`tokyo-night.gpl`) — dark paper

| Color | Hex |
| --- | --- |
| Background | `#1a1b26` |
| Comment | `#565f89` |
| Red | `#f7768e` |
| Orange | `#ff9e64` |
| Yellow | `#e0af68` |
| Green | `#9ece6a` |
| Teal | `#73daca` |
| Cyan | `#2ac3de` |
| Light Blue | `#7dcfff` |
| Blue | `#7aa2f7` |
| Magenta | `#bb9af7` |
| Light Cyan | `#b4f9f8` |
| Editor Foreground | `#a9b1d6` |
| Foreground | `#c0caf5` |

### Tokyo Night Light (`tokyo-night-light.gpl`) — light paper

| Color | Hex |
| --- | --- |
| Background | `#e6e7ed` |
| Comment | `#6c6e75` |
| Red | `#8c4351` |
| Orange | `#965027` |
| Yellow | `#8f5e15` |
| Tan | `#634f30` |
| Green | `#385f0d` |
| Teal | `#33635c` |
| Cyan | `#006c86` |
| Light Blue | `#0f4b6e` |
| Blue | `#2959aa` |
| Magenta | `#5a3e8e` |
| Text | `#40434f` |
| Foreground | `#343b58` |

### Tokyo Night Mix (`tokyo-night-mix.gpl`) — all papers

| Color | Hex | Source |
| --- | --- | --- |
| Ink Dark | `#1a1b26` | Night Background |
| Grey | `#6c6e75` | Light Comment |
| Red | `#8c4351` | Light |
| Orange | `#965027` | Light |
| Yellow | `#8f5e15` | Light |
| Green | `#385f0d` | Light |
| Teal | `#33635c` | Light |
| Cyan | `#006c86` | Light |
| Blue | `#2959aa` | Light |
| Magenta | `#5a3e8e` | Light |
| Ink Light | `#c0caf5` | Night Foreground |

## Credits

Colors by [enkia](https://github.com/tokyo-night/tokyo-night-vscode-theme)
([MIT](https://github.com/tokyo-night/tokyo-night-vscode-theme/blob/master/LICENSE)).
Palette layout inspired by the [Dracula Xournal++ port](https://draculatheme.com/xournalpp).

## License

MIT — see [LICENSE](LICENSE).
