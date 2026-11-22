# System24 themes for Vesktop

Four palettes for Vesktop: Gruvbox, Kanagawa Dragon, Rosé Pine Dawn, and
Solitude. Each uses System24’s square panels, panel labels, ASCII channel
headings, and ASCII loader.

## Install

Copy a `*.theme.css` file to `~/.config/vesktop/themes/` on Linux. In Vesktop,
go to **Themes → Local Themes** and enable one palette at a time.

Text and code use your system monospace font. The themes load the upstream
System24 stylesheet for the ASCII styling.

## 90% window opacity on Hyprland

Add this rule to your Hyprland Lua configuration to set Vesktop to 90%
opacity with any palette.

```lua
hl.window_rule({
  name = "vesktop-translucency",
  match = { class = "^vesktop$" },
  opacity = "0.90 0.90 0.90",
})
```

Based on [System24](https://github.com/refact0r/system24) and
[midnight-discord](https://github.com/refact0r/midnight-discord) by refact0r.
