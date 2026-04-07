<p align="center">
  <img src="assets/owl.png" alt="Gruvbit owl" width="160" height="160">
</p>

<h1 align="center">Gruvbit for VS Code</h1>

A Visual Studio Code color theme — faithful port of [vim-gruvbit](https://github.com/habamax/vim-gruvbit) by Maxim Kim.

Based on gruvbox hard dark background with refined color mappings. Less reddish, more yellowish. No bold or italic except for headings/titles — staying true to the original.

## Color Palette

| Role         | Color   | Hex       |
|-------------|---------|-----------|
| Background  | ![bg]   | `#1d2021` |
| Foreground  | ![fg]   | `#ebdbb2` |
| Red         | ![red]  | `#e9593d` |
| Green       | ![grn]  | `#8ec07c` |
| Yellow      | ![yel]  | `#dc9656` |
| Blue        | ![blu]  | `#83a598` |
| Magenta     | ![mag]  | `#d3869b` |
| Cyan        | ![cyn]  | `#496d79` |
| Orange      | ![org]  | `#fe8019` |
| Bright Yellow | ![byel] | `#fabd2f` |
| Comment     | ![cmt]  | `#968772` |
| UI Gray     | ![gry]  | `#444444` |
| Selection   | ![sel]  | `#475048` |
| Line Highlight | ![lhl] | `#2d3031` |

[bg]: https://via.placeholder.com/16/1d2021/1d2021
[fg]: https://via.placeholder.com/16/ebdbb2/ebdbb2
[red]: https://via.placeholder.com/16/e9593d/e9593d
[grn]: https://via.placeholder.com/16/8ec07c/8ec07c
[yel]: https://via.placeholder.com/16/dc9656/dc9656
[blu]: https://via.placeholder.com/16/83a598/83a598
[mag]: https://via.placeholder.com/16/d3869b/d3869b
[cyn]: https://via.placeholder.com/16/496d79/496d79
[org]: https://via.placeholder.com/16/fe8019/fe8019
[byel]: https://via.placeholder.com/16/fabd2f/fabd2f
[cmt]: https://via.placeholder.com/16/968772/968772
[gry]: https://via.placeholder.com/16/444444/444444
[sel]: https://via.placeholder.com/16/475048/475048
[lhl]: https://via.placeholder.com/16/2d3031/2d3031

## Syntax Mapping

| Element      | Color         |
|-------------|---------------|
| Keywords    | Bright Yellow `#fabd2f` |
| Strings     | Green `#8ec07c` |
| Functions   | Blue `#83a598` |
| Types       | Bright Yellow `#fabd2f` |
| Constants   | Magenta `#d3869b` |
| Comments    | Comment Gray `#968772` |
| Tags        | Yellow `#dc9656` |
| Special     | Red `#e9593d` |
| Preprocessor| Yellow `#dc9656` |
| Delimiters  | Brown `#a16946` |

## Installation

### From Marketplace

1. Open VS Code
2. Go to Extensions (`Ctrl+Shift+X` / `Cmd+Shift+X`)
3. Search for `Gruvbit`
4. Click **Install**
5. `Ctrl+K Ctrl+T` / `Cmd+K Cmd+T` → select **Gruvbit**

### From VSIX

1. Download the `.vsix` file from [Releases](https://github.com/REPLACE-ME/vscode-gruvbit/releases)
2. Run: `code --install-extension gruvbit-0.1.0.vsix`

### From Source

```sh
git clone https://github.com/REPLACE-ME/vscode-gruvbit
cd vscode-gruvbit
npm install -g @vscode/vsce
vsce package
code --install-extension gruvbit-0.1.0.vsix
```

## Credits

- **Maxim Kim** ([@habamax](https://github.com/habamax)) — author of [vim-gruvbit](https://github.com/habamax/vim-gruvbit)
- **Pavel Pertsev** ([@morhetz](https://github.com/morhetz)) — author of [gruvbox](https://github.com/morhetz/gruvbox), the colorscheme gruvbit is based on

## License

MIT
