# Nerd-Sarasa-Merge

[Droid Sans Mono](https://www.1001fonts.com/droid-sans-mono-font.html) / [Monaspace](https://monaspace.githubnext.com/) x [Sarasa Gothic](https://github.com/be5invis/Sarasa-Gothic)

Merge fonts with [Warcraft Font Merger](https://github.com/nowar-fonts/Warcraft-Font-Merger)(魔兽世界字体合并/补全工具).

I've been using `MonaspiceArNerdFontPropo-Regular` in [Sublime Text](https://www.sublimetext.com/) and [Termux](https://termux.dev/en/).

## How to make (On Windows 10)

Install fonts:

```sh
scoop install DroidSansMono-NF-Propo
scoop install Monaspace-NF-Propo
scoop install SarasaGothic-SC
...
```

Download [releases](https://github.com/nowar-fonts/Warcraft-Font-Merger/releases) of WFM.

Decompress the archive. Rename it to `Warcraft-Font-Merger`.

Go to `C:\Users\yourname\AppData\Local\Microsoft\Windows\Fonts`, copy `thefont.otf`, `sarasa-gothic-sc-regular.ttf` to `Warcraft-Font-Merger/_font`.

```sh
cd Warcraft-Font-Merger
合并补全.bat _font/thefont.otf _font/sarasa-gothic-sc-regular.ttf
```

Rename the `out.ttf`.

## How to use

For example, `Sublime Text → Preferences → Settings`, edit:

```
{
	"font_face": "MonaspiceAr NFP + Sarasa Gothic SC + WFM Sans SC",
  "font_options": [
    "directwrite",
    "dwrite_cleartype_natural",
    "dlig", // Optional
    "ss01", // Optional
  ],
}
```

## Disclaimer

Just a disclaimer, blah blah blah...