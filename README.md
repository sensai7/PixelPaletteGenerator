# Pixel Palette Generator

This project can be used at [https://sensai7.github.io/PixelPaletteGenerator/](https://sensai7.github.io/PixelPaletteGenerator/).

Pixel Palette Generator is a small browser-based tool for creating color palettes from a selected middle tone. Adjust the hue, floor, saturation shift, hue shift, and number of colors to explore variations, then add palettes to the saved area and download them as `.GPL` files for use with GIMP and compatible software.

## Running locally

No build step or package installation is needed. Open `index.html` in a web browser, or serve the project with any simple local web server.

For example, with Python installed:

```bash
python -m http.server
```

Then visit `http://localhost:8000`.

## Contributing

1. Fork or clone the repository.
2. Make changes in `index.html`.
3. Open the page locally and test color generation, resets, palette saving, and `.GPL` downloads.
4. Keep the interface accessible and avoid adding dependencies unless they are necessary.
5. Submit a pull request describing the change.

## Project structure

- `index.html` — page markup, styles, palette-generation logic, and download functionality.
- `README.md` — project and contribution notes.

## Credits

Created by [Gonzalo Letterer](https://x.com/GonzaloLetterer).
