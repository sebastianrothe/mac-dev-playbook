# Mac Dev Setup
1. Turn off Bluetooth
1. Install Ansible (https://github.com/geerlingguy/mac-dev-playbook#installation)
  1. export PATH="$HOME/Library/Python/3.8/bin:/opt/homebrew/bin:$PATH"
1. sudo chown -R $(whoami) /opt/homebrew
1. sudo softwareupdate --install-rosetta --agree-to-license
1. Run ansible playbook
1. Change Wallpaper
1. Disable Interface sounds
1. Disable screensaver
1. Reduce Spotlight to Applications, Settings only
1. Safari Config (Adblocker, DuckDuckGo, KeepassXc)
1. Symlink SSH config
1. Firefox configuration: https://github.com/jakeprice-dev/ansible-macbook-macos/blob/master/playbook.yml#L276
  1. Facebook container, uBlock, unhook, Keepassxc, enhancer, 
  1. Optional extensions: https everywhere, dark reader
  1. Settings, Cookies, Search Engine, Passwords, HTTPS, Privacy
1. Chrome config
1. Switch locale to English, region to Germany
1. Add input sources: german, US international, US
1. Disable Ad targeting
1. Install node LTS + latest (n with N_PREFIX=$HOME/.n)
1. Setup ZSH (zsh4humans, dotfiles, powerlevel10k)
1. Setup VIM (NeoVIM, 8+ Extensions)
1. Unhide Sound icon in Statusbar
1. Disable audio bell on Terminal profile
1. Remap Esc-Caps Lock for internal keyboard
1. macFUSE: ext2, ext4
1. Dock positions
1. Show HomeFolder, Harddrive in Finder
1. Configure Hot Corners
1. Start ScrollReverser, Rectangle, Raycast
1. Start Android Studio
1. Configure VSCode
  - Settings
  - Themes
  - Extensions
1. Configure Multipass
  - Add SSH-Key to Multipass Docker VM
  - Add Multipass IP to /etc/hosts
1. Copy Backups
  - SSH
  - Documents
  - Downloads
  - Photos
  - Videos
  - Little Snitch
  - Karabiner
  - MoneyMoney
  - IntelliJ
  - Thunderbird Profile
  - Multipass VM
  - Parallels VM
  - PGP Keys
1. Display settings
  - Add ICC profile to /Library/ColorSync/Profiles/Display
1. Change hostname
  - `sudo hostname mbp-srothe`
  - System preferences -> Sharing
1. Set NTP Server to 0.de.pool.ntp.org
1. Add licenses
  - MoneyMoney
  - LittleSnitch
  - MicroSnitch
  - iStatMenus
  - Timing
  - Arq
1. Start Tor and Nyx
1. Add printer drivers
  - https://support.apple.com/kb/DL1888?locale=en_US