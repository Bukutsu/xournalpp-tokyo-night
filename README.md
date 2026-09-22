# Tokyo Night palettes for Xournal++

Three pen palettes for [Xournal++](https://xournalpp.github.io/), based on
[enkia's Tokyo Night VS Code theme](https://github.com/tokyo-night/tokyo-night-vscode-theme).

![Palette preview](preview.png)

## Choose a palette

| File | Paper | Notes |
| --- | --- | --- |
| `tokyo-night.gpl` | Dark | Bright Tokyo Night colors with the full glow. Colors are too light for white paper. |
| `tokyo-night-light.gpl` | Light | Darker versions of the Tokyo Night colors for light paper. |
| `tokyo-night-mix.gpl` | White, light, dark, or black | Muted colors that stay readable across all four paper types. |

The Mix palette is the practical default when you change page backgrounds. Mid-grey
paper is outside its readability guarantee.

## Install

1. Download `tokyo-night-palettes.zip` from the
   [Releases](https://github.com/Bukutsu/xournalpp-tokyo-night/releases) page.
2. Unzip it and copy the three `.gpl` files to Xournal++'s `palettes` folder:

   | System | Folder |
   | --- | --- |
   | Linux | `/home/<you>/.config/xournalpp/palettes/` |
   | macOS | `/Users/<you>/.config/xournalpp/palettes/` |
   | Windows | `C:\Users\<you>\AppData\Local\xournalpp\palettes\` |

   On Windows, `AppData` is hidden. Paste the path into File Explorer's address
   bar and replace `<you>` with your username.
3. Restart Xournal++, then select a palette in `Edit > Preferences > Palette`.

With git:

```sh
git clone https://github.com/Bukutsu/xournalpp-tokyo-night.git
```

Copy the `.gpl` files from the clone to the same `palettes` folder.

## Match the page background

Set the page background in `Journal > Configure Page Template`:

- Night: `#1a1b26`
- Light: `#e6e7ed`

The Mix palette works with white, light, dark, and black paper.

## See the colors

The preview above shows the palettes as they look on the page. Pick Night for
bright colors on dark paper, Light for darker colors on light paper, or Mix when
you use more than one kind of paper.

The exact colors are stored in the `.gpl` files. You do not need to choose them
individually.

## Credits

Colors come from [enkia's Tokyo Night VS Code theme](https://github.com/tokyo-night/tokyo-night-vscode-theme)
under the [MIT license](https://github.com/tokyo-night/tokyo-night-vscode-theme/blob/master/LICENSE).
The palette layout follows the [Dracula Xournal++ port](https://draculatheme.com/xournalpp).

## License

MIT. See [LICENSE](LICENSE).
