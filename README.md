# Accented

A lightweight theme for [Spicetify](https://github.com/spicetify) that replaces Spotify's green with a color of your choice.

![preview](./img/preview.png)

This theme was originally created by [@luximus-hunter](https://github.com/luximus-hunter) in Feb of 2022, survived by [@updxg](https://github.com/updxg)'s fork (among others) after it was deleted or privated, then updated to reappear on the marketplace on this fork.

## Color options

- Red
- Orange
- Yellow
- Green
- Blue
- Purple
- Magenta
- Pink
- White
- Full White (also hearts)

## Installation

> [!WARNING]
> These installation methods may not currently work as of 2025-11-25. Especially for this fork ([@JWWolstenholme](https://github.com/JWWolstenholme/accented)).

**Spicetify Marketplace** (recommended)

Install the theme though the [Spicetify Marketplace](https://github.com/spicetify/marketplace). This will allow you to change the color quickly in-app.

![colors](./img/colors.png)

**Linux and MacOS** in Bash:

```bash
cd "$(dirname "$(spicetify -c)")/Themes"
git clone https://github.com/JWWolstenholme/accented
```

**Windows** in Powershell:

```powershell
cd "$(spicetify -c | Split-Path)\Themes"
git clone https://github.com/JWWolstenholme/accented
```

## Development

1. Install [npm](https://www.npmjs.com/)
1. Install [sass](https://sass-lang.com/): `npm install -g sass`
1. Edit [`user.scss`](/user.scss). **Not** `user.css`.
1. Run `sass --no-source-map user.scss:user.css` to compile and output to the [`user.css`](/user.css) file