# Mecha Green

![Mecha Green](preview.png)

Military olive, visor amber and worn steel for Omarchy. Inspired by Halo's
Master Chief and the MCHOSE Ace 75 Mecha Green keyboard.

## Install

From this repository:

```sh
omarchy theme install https://github.com/sazardev/omarchy-mecha-green-theme
```

Once the registry listing is live, the short form is:

```sh
omarchy theme install mecha-green
```

The marketplace install keeps the palette, shell surfaces, btop, Chromium,
icons, keyboard RGB, unlock art and wallpapers. Omarchy regenerates the
terminal and Hyprland configs from `colors.toml`, so a theme installed from a
repository stays colours-only.

## Palette

| Role | Hex |
|---|---|
| Background | `#0E1009` |
| Raised surface | `#11150B` |
| Military olive | `#9DAE5C` |
| Visor amber / accent | `#F2C84B` |
| Sand text | `#D8D9B4` |
| Sage | `#BCC09A` |
| Rust | `#C85B47` |
| HUD teal | `#7FA89A` |

The theme sets `mode = "dark"` and styles the bar, menus, notifications,
launcher, OSD, lock screen, btop, Chromium, Neovim, Helix and the terminal
through Omarchy's normal palette generation.

## Wallpapers

Eight original 2560×1440 pieces, licensed MIT together with the theme:

| | |
|---|---|
| ![](backgrounds/8-mecha-helmet.webp)<br>**Mecha helmet** — geometric Spartan helmet and amber visor | ![](backgrounds/9-topographic.webp)<br>**Topographic HUD** — olive contours and a targeting reticle |
| ![](backgrounds/10-keyboard.webp)<br>**MCHOSE Ace 75** — product-style keyboard render | ![](backgrounds/11-switch-blueprint.webp)<br>**Hall Effect switch** — cross-section and top view |
| ![](backgrounds/12-pcb-blueprint.webp)<br>**PCB blueprint** — 75% keyboard matrix | ![](backgrounds/13-radar.webp)<br>**Tactical radar** — contacts and threat readout |
| ![](backgrounds/14-helmet-blueprint.webp)<br>**Helmet schematic** — MJOLNIR dimensions | ![](backgrounds/15-crate.webp)<br>**Supply crate** — stencil and hazard strip |

Switch them with `omarchy theme bg next`, or pick one from the theme folder.

## Included

- `colors.toml` — the full dark palette and `mode = "dark"`.
- `shell.toml` — olive-black appbar, amber indicators, gradient borders,
  amber-tinted menus, launcher, lock screen and 28 px bar.
- `btop.theme`, `chromium.theme`, `icons.theme` (`Yaru-olive`) and
  `keyboard.rgb`.
- `unlock.png` and `preview-unlock.png` — amber Omarchy mark on dark olive.
- `preview.png` — 16:9 theme preview.
- `backgrounds/` — the eight originals above.

## Full project

The companion repository
[`sazardev/omarchy-mecha-green`](https://github.com/sazardev/omarchy-mecha-green)
adds:

- **Mecha Green Light**, a sand/bronze daylight twin.
- **Mecha HUD** and **Mecha NET** bar widgets with latency, CPU, RAM and
  battery telemetry.
- `mecha-status`, `mecha-themetize` and the optional Halo/military wallpaper
  fetcher with curated Spartans, UNSC, Covenant and Forerunner sets.
- **SDDM login** and **Plymouth boot** themes plus lock-screen previews.
- The two-theme `install.sh` for the complete setup.

## License

Theme configuration, scripts and original artwork are MIT. See [LICENSE](LICENSE).

Halo, Master Chief, MCHOSE and Omarchy are trademarks of their respective
owners. This is a personal fan theme, not affiliated with or endorsed by
Microsoft, 343 Industries, MCHOSE or Omarchy.
