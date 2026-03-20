# niri.config

My personal dotfiles for a Wayland desktop built around [niri](https://github.com/niri-wm/niri) — a scrollable tiling compositor. Running on NixOS; the system-level configuration lives at [cybergaz/nixos.config](https://github.com/cybergaz/nixos.config).

---

## Components

| Role | Tool |
|---|---|
| Compositor | [niri](https://github.com/niri-wm/niri) |
| Bar | [waybar](https://github.com/Alexays/Waybar) |
| Launcher / Menus | [wofi](https://hg.sr.ht/~scoopta/wofi) |
| Terminal | [alacritty](https://github.com/alacritty/alacritty)|
| Shell | [fish](https://fishshell.com) |
| Notifications | [mako](https://github.com/emersion/mako) |
| Display Manager | [ly](https://github.com/fairyglade/ly) |
| Multiplexer | tmux |

---

## Scripts

Works best with my own scripts for various tasks, which lives at [cybergaz/scripts](https://github.com/cybergaz/scripts)


## Usage

Clone and symlink (or copy) the relevant directories into `~/.config/`:

```sh
git clone https://github.com/cybergaz/niri-conf
cd niri-conf
stow --target=$HOME/.config config   # if you use GNU stow
```

Or manually link individual configs as needed.

> For NixOS home-manager / system setup, see [cybergaz/nixos.config](https://github.com/cybergaz/nixos.config).
