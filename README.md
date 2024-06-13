# Simplemoji 😁
An application where you can have all the emojis with easy and quick access

<p align="center">
  <img alt="GitHub Workflow Status (with event)" src="https://img.shields.io/github/actions/workflow/status/SergioRibera/simplemoji/ci.yml?label=ci">
  <img alt="GitHub Workflow Status (with event)" src="https://img.shields.io/github/actions/workflow/status/SergioRibera/simplemoji/release.yml">
  <img alt="AUR version" src="https://img.shields.io/aur/version/simplemoji?link=https%3A%2F%2Faur.archlinux.org%2Fpackages%2Fsimplemoji">
  <img alt="GitHub release (with filter)" src="https://img.shields.io/github/v/release/SergioRibera/simplemoji?link=https%3A%2F%2Fgithub.com%2FSergioRibera%2FSimplemoji%2Freleases">
</p>

<p align="center">
  <img src="https://github.com/SergioRibera/Simplemoji/assets/56278796/06d1bc25-d19e-423e-a986-11b80d0e8351" />
</p>

> [!NOTE]
> The shortcut with which you launch the application must be configured on your own according to the WindowManager you have

# Features
- 🔎 Searchbar
- 👋 Tone emoji selector
- 👁️ Preview block
- ©️ Copy to clipboard
- 🎨 Custom UI Colors
- ⚡ Blazing Fast
- 🐧 Crossplatform (Linux (X11/Wayland), MacOs)

# 🎨 Custom UI Colors
![SimplemojiTheme](https://github.com/SergioRibera/Simplemoji/assets/56278796/fc7a9b2f-c395-4f66-b5fc-e2153c5372f0)

For this we use the arguments of the application, for example
```sh
simplemoji -m '#000' -b '#DEA584'
```

```sh
simplemoji -m '#d485ad' --background-color '#262626'
```

```sh
simplemoji --primary-color '#c9cbd1' --background-color '#f2ecbc'
```


# 💽 Installation
Requirements:
 - Install [Noto Color Emoji](https://fonts.google.com/noto/specimen/Noto+Color+Emoji) font on your system

Options:
- Download from [releases](https://github.com/SergioRibera/Simplemoji/releases)
- If you use ArchLinux, just install from [Aur](https://aur.archlinux.org/packages/simplemoji)

# 🙇 Usage
```
Usage: simplemoji [OPTIONS]

Options:
  -t, --tone <TONE>
          [possible values: default, light, medium-light, medium, medium-dark, dark]
  -s, --show-search

  -p, --show-preview

  -o, --close-on-copy

  -x, --no-close
          By default the application closes automatically when it is out of focus, this option disables that behavior
  -b, --background-color <BACKGROUND_COLOR>
          Background color in hex (RGB, RGBA, RRGGBB, RRGGBBAA)
  -m, --primary-color <PRIMARY_COLOR>
          Primary color in hex (RGB, RGBA, RRGGBB, RRGGBBAA)
  -c, --copy-command <COPY_COMMAND>
          This is the command that will be executed to copy the emoji
  -h, --help
          Print help
  -V, --version
          Print version
```
