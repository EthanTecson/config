

# macOS Dotfiles Setup### AeroSpace InstallationAeroSpace is an i3-like tiling window manager for macOS.
1. **Install via Homebrew:**
   ```bash
   brew install --cask nikitabobko/tap/aerospace


   1. Grant Permissions:
   Go to System Settings > Privacy & Security > Accessibility and enable AeroSpace.
   2. Config Location:
   Place your configuration at ~/.config/aerospace/aerospace.toml.
   3. Run:
   Launch AeroSpace from your Applications folder or via Spotlight.

------------------------------
Ghostty Installation
Ghostty is a high-performance, GPU-accelerated terminal emulator.

   1. Install via Homebrew:
   
   brew install --cask ghostty
   
   2. Config Location:
   Place your configuration at ~/.config/ghostty/config.
   3. Explore Settings:
   To see all available configuration options, run:
   
   ghostty +show-config --default --docs
   
   
------------------------------
Syncing Configs (Optional)
To use the files from this repository, symlink them to your home directory:

ln -s ~/path/to/your/repo/aerospace/aerospace.toml ~/.config/aerospace/aerospace.toml
ln -s ~/path/to/your/repo/ghostty/config ~/.config/ghostty/config
