# 🔴 OmarchyThings

An [Omarchy](https://omarchy.org) theme inspired by Stranger Things. Poster black,
blood red, a thin teal horizon, and amber city lights. Dark first, readable
always.

![Desktop preview](preview.png)

## ✨ What you get

- **Palette** built from the Season 5 poster: near-black background, deep red
  accent, muted teal and amber secondaries. Text is a warm cream at roughly
  10:1 contrast, so it is easy on the eyes for long sessions.
- **Everything themed at once**: terminals (foot, Alacritty, Kitty, Ghostty),
  Neovim, btop, Helix, the Omarchy bar, launcher, notifications, lock screen,
  Chromium, VS Code, Obsidian, Claude Code, and the keyboard backlight.
- **Window borders** fade from poster red into dried-blood red.
- **Six 4K wallpapers** of the Upside Down, Hawkins, and red storm skies.

## 📦 Install

```bash
omarchy theme install https://github.com/itsMattGuenther/omarchy-omarchy-things-theme.git
```

The theme is applied right away. Later, switch with:

```bash
omarchy theme set omarchy-things
omarchy theme bg next        # cycle wallpapers
```

## 🎨 Wallpapers

![Wallpapers](docs/wallpapers.jpg)

Six variants live in `backgrounds/`, all 3840x2160. Add your own next to
them, or drop extra images into `~/.config/omarchy/backgrounds/omarchy-things/`
to keep them out of the theme folder.

## 🔐 The lock screen

The lock screen (Super+Escape) shows a blurred copy of whichever wallpaper you
are on, with the theme's colors on the password box. That is how Omarchy
builds it, and no theme can put its own artwork there.

There is an `unlock.png` in this repo, but it is not the lock screen. Omarchy
only uses that file if you open **Style > Unlock** in the Omarchy menu and
deliberately switch your *boot* screen to this theme, which asks for your
password and rebuilds your boot image. Installing this theme leaves all of that
alone. I would rather a theme did not go anywhere near your boot setup.

## 👾 Extras (optional)

![Eleven greeting and the Demogorgon About screen](https://github.com/itsMattGuenther/omarchy-theme-extras/raw/main/omarchy-things/docs/preview-extras.png)

A Demogorgon on the About screen, Eleven greeting you in every new terminal,
and a matching theme for the cliamp music player. A theme can't ship the
script that puts these in place, so they live in
[omarchy-theme-extras](https://github.com/itsMattGuenther/omarchy-theme-extras/tree/main/omarchy-things), with install and
uninstall steps.

## 🛠️ Hacking on it

- `colors.toml` is the whole palette. The contrast checker for it lives with
  the [extras](https://github.com/itsMattGuenther/omarchy-theme-extras/tree/main/omarchy-things).
- `docs/OMARCHY-THEME-REFERENCE.md` explains how Omarchy turns that file into
  every app config, and which files a git-installed theme is not allowed to
  ship.
- `preview-unlock.png` is the tile Omarchy shows in its **Style > Unlock**
  picker. The script that regenerates it lives with the extras too.

## 🙏 Credits

- Built on Omarchy's theme system by DHH and the Omarchy community.
- Made with help from Claude and Grok. Mentioned here because I'd rather be
  transparent about it.

## 🤝 Contributing

I'd gladly take help from anyone who wants to iterate on this: upscaling the
wallpapers properly, better art, palette tweaks, new extras, anything. Open an
issue or a pull request. I'm here for the community <3

## ⚖️ License and disclaimer

MIT, see `LICENSE`.

Fan-made and unofficial. Not affiliated with Netflix or the creators of
Stranger Things. No official artwork, logos, or fonts are included.
