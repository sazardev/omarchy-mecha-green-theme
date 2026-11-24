# Mecha Green

![Mecha Green](preview.png)

**Flat topographic wallpapers, olive surfaces and amber accents for Omarchy dark mode.**

## Install

```sh
omarchy theme install https://github.com/sazardev/omarchy-mecha-green-theme
omarchy theme set "Mecha Green"
```

## Included

- `colors.toml` and `shell.toml` for the complete dark theme.
- btop, Chromium, icon and keyboard colour configuration.
- Seven native 3840×2160 (4K) lossless WebP wallpapers.
- Six clean 8-second native 4K H.264 live wallpaper loops.
- `0-topographic.webp` as the default.

## Wallpapers

| Set | Designs |
|---|---|
| Default | `0-topographic` |
| Collection | `100-drift`, `101-fold`, `102-field`, `103-terrain`, `104-panorama`, `105-undulate` |

Every asset is rendered directly from the original SVG artwork without upscaling.
Live loops animate only the contour lines; the Geist wordmark stays fixed.

## Login and boot screens

Install the matching SDDM login and Plymouth splash:

```sh
sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/sazardev/omarchy-mecha-green/main/system/install-login.sh)"
```

The installer backs up your configuration and rebuilds the initramfs.

## Full project

[`sazardev/omarchy-mecha-green`](https://github.com/sazardev/omarchy-mecha-green) adds the light theme, HUD widgets, CLI tools, wallpaper generators and system-screen sources.

## License

MIT. See [LICENSE](LICENSE).
