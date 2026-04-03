# Night Owl Black for Zed

Night Owl Black is a Zed theme extension with a true black editor background, muted chrome, and the bright Night Owl accent palette carried over into syntax highlighting.

It is designed for people who like the Night Owl family of themes but want a darker UI with less glow from surrounding surfaces.

## Included theme

- `Night Owl Black`

## Installation

### From source

Clone this repository and symlink it into Zed's installed extensions directory:

```sh
mkdir -p ~/Library/Application\ Support/Zed/extensions/installed
ln -s /absolute/path/to/night-owl-black-zed-theme \
  ~/Library/Application\ Support/Zed/extensions/installed/night-owl-black
```

Restart Zed, then open the theme picker and select `Night Owl Black`.

### Manual selection in settings

If you prefer to set it directly:

```json
{
  "theme": {
    "mode": "dark",
    "dark": "Night Owl Black"
  }
}
```

## Development

The extension manifest lives in `extension.toml`, and the theme definition lives in `themes/NightOwlBlack.json`.

After making changes, reload Zed to see the updated theme.

## Credits

This project is an independent Zed port inspired by the Night Owl Black visual style created for VS Code by Dave Johnson, and by the existing Night Owl Zed port from the Zed ecosystem.

## License

MIT. See [LICENSE](LICENSE).
