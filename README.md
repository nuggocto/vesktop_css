# System24 Lite themes for Vesktop

Copy one of the root `*.theme.css` files to your Vesktop themes folder
(`~/.config/vesktop/themes/` on this Linux setup) and enable it under
**Themes → Local Themes**. If the installed file is a symlink, move the
symlink aside before copying so you don't overwrite its target. Enable only
one palette at a time.

Each file includes the shared styles and loads no remote CSS, fonts, or images.
The themes keep the palettes, monospace text, and square panel borders.
Discord handles layout, status icons, and loaders. These versions don't
include System24's outside panel labels, ASCII art, or animated hover effects.
The configured fonts are used if installed; otherwise the themes use the
system monospace font.

If scrolling or typing still stutters, toggle **Enable Custom CSS** off and
retry with just one theme. QuickCSS and other themes can add their own costly
rules independently.

Based on [System24](https://github.com/refact0r/system24) and
[midnight-discord](https://github.com/refact0r/midnight-discord) by refact0r.
