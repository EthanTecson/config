# macOS Dotfiles

Config files for AeroSpace, Ghostty, and JankyBorders.

---

## 1. Install Dependencies

Run this to install everything at once:
```bash
brew install --cask nikitabobko/tap/aerospace
brew install --cask ghostty
brew install FelixKratz/formulae/borders
```

---

## 2. Symlink Configs

Run from the root of this repo:
```bash
ln -s "$(pwd)/aerospace/aerospace.toml" ~/.config/aerospace/aerospace.toml
ln -s "$(pwd)/ghostty/config" ~/.config/ghostty/config
```

---

## 3. Grant Accessibility Permission (AeroSpace)

1. Open **System Settings > Privacy & Security > Accessibility**
2. Enable **AeroSpace**

---

## 4. Start Everything

**AeroSpace** — launch from Applications or Spotlight. It will automatically start JankyBorders on launch (configured in `aerospace.toml`).

**Ghostty** — launch from Applications or Spotlight.

> JankyBorders is started and managed by AeroSpace via `after-startup-command` in the config. You do not need to start it manually.

---

## What Each Tool Does

| Tool | Purpose |
|------|---------|
| AeroSpace | i3-like tiling window manager |
| Ghostty | GPU-accelerated terminal emulator |
| JankyBorders | Highlights the active window with a colored border |
