# Rosé Pine Dark — Omarchy theme

![preview](preview.png)

The official **[Rosé Pine](https://rosepinetheme.com/)** "Main" (dark) palette,
adapted for [Omarchy](https://omarchy.org/). Omarchy ships a stock `rose-pine`
theme, but it's actually the light **Dawn** variant — this theme is the real
dark one.

## Install

```
Omarchy Menu > Install > Style > Theme
```

Paste this repo's URL, or from the terminal:

```bash
omarchy theme install https://github.com/otavioschwanck/omarchy-rose-pine-dark-theme
```

## Colors

All hex values in `colors.toml` come straight from the official
[`rose-pine/palette`](https://github.com/rose-pine/palette) CSS distribution
(the "Main" / dark variant — `base`, `surface`, `overlay`, `love`, `gold`,
`rose`, `pine`, `foam`, `iris`, `highlight low/med/high`).

Two slots (`orange` and `brown`) aren't part of the official Rosé Pine
palette — Omarchy's own stock `rose-pine` (Dawn) theme invents them too, by
blending `love` and `gold` at 100% and 50% respectively. This theme follows
the exact same formula so the dark and light variants stay visually
consistent:

- `orange` = midpoint of `love` and `gold`
- `brown` = `orange` darkened by 50%

## Credits

- Palette: [Rosé Pine](https://github.com/rose-pine/palette) (MIT)
- Wallpapers: see [`CREDITS.md`](CREDITS.md)
