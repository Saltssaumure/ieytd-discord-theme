[screenshot]:       https://user-images.githubusercontent.com/29710355/150716493-d073d3f6-4bcc-4003-ae01-1a1eb820bb71.png
[customised]:       https://user-images.githubusercontent.com/29710355/158090723-f7b872b6-8532-41ce-9476-21d1aa7a89a3.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-bd-dl]:     https://img.shields.io/github/downloads/Saltssaumure/ieytd-discord-theme/Tritone.theme.css?color=purple&label=Downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/Saltssaumure/ieytd-discord-theme/net.saltssaumure.Tritone.asar?color=purple&label=Downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/Saltssaumure/ieytd-discord-theme?label=Repository&style=flat-square "Total size"

[github]:           https://github.com/Saltssaumure/ieytd-discord-theme
[license]:          https://github.com/Saltssaumure/ieytd-discord-theme/blob/main/LICENSE
[issues]:           https://github.com/Saltssaumure/ieytd-discord-theme/issues
[.theme.css]:       https://github.com/Saltssaumure/ieytd-discord-theme/blob/main/Tritone.theme.css

[release-bd]:       https://betterdiscord.app/theme/?id=626 "BetterDiscord store page"
[release-bd-gh]:    https://github.com/Saltssaumure/ieytd-discord-theme/releases/latest/download/Tritone.theme.css "Get latest release"
[release-rp]:       https://replugged.dev/store/net.saltssaumure.Tritone "Replugged store page"
[release-rp-gh]:    https://github.com/Saltssaumure/ieytd-discord-theme/releases/latest/download/net.saltssaumure.Tritone.asar "Get latest release"

# Tritone Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![BetterDiscord GitHub downloads][shield-bd-dl]][release-bd-gh]
[![Replugged GitHub downloads][shield-asar-dl]][release-rp-gh]
[![Total repository size][shield-repo-size]][github]

***A tri-tone Discord theme inspired by the ["I Expect You To Die" intro sequence](https://www.youtube.com/watch?v=ht1ZChKF4Ek).***

![Screenshot of Tritone applied to Discord][screenshot]

## Installation

### BetterDiscord
1. Install [BetterDiscord][BetterDiscord].
2. Download the theme file:
    - [BetterDiscord store][release-bd]
    - [GitHub][release-bd-gh]
3. Place theme file in the theme folder:
    - Windows: `%AppData%/BetterDiscord/themes`
    - Mac: `~/Library/Application Support/betterdiscord/themes`
    - Linux: `~/.config/BetterDiscord/themes`

### Replugged
1. Install [Replugged][Replugged].
2. Install the theme:
    - [Replugged store][release-rp]
    - [GitHub][release-rp-gh]

### Vencord
1. Install [Vencord][Vencord].
2. Paste the following in `Settings` > `Vencord` > `Themes`:
    - `https://saltssaumure.github.io/ieytd-discord-theme/Tritone.theme.css`

## Customisation

![Tritone theme with customised colours][customised]

| Description | Variable name     | Valid values             | Default value     | Demo value       |
| ----------- | ----------------- | ------------------------ | ----------------- | ---------------- |
| Colour 1    | `--ieytd-color-1` | Any [colour][css-color]. | `#C34938` (red)   | `#600` (crimson) |
| Colour 2    | `--ieytd-color-2` | Any [colour][css-color]. | `#E1CC9A` (cream) | `#AAA` (silver)  |
| Colour 3    | `--ieytd-color-3` | Any [colour][css-color]. | `#000000` (black) | `#000` (black)   |

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Replugged
1. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste line 15-20 of [`Tritone.theme.css`][.theme.css].
3. Edit the variable values and apply changes.

### Vencord
#### Standard method
1. Follow the instructions in `Settings` > `Vencord` > `Themes`.
#### Recommended method
1. Open `Settings` > `Vencord` > `Vencord`.
2. Toggle on `Enable Custom CSS` and click `Open QuickCSS File`.
3. Copy and paste line 15-20 of [`Tritone.theme.css`][.theme.css].
4. Edit the variable values.

## License
[GNU General Public License v3.0][license]
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, as long as you allow others to do the same with your version.

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].