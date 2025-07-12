# Mac Dev Setup
1. Turn off Bluetooth
1. Install Ansible (https://github.com/geerlingguy/mac-dev-playbook#installation)
  1. export PATH="$HOME/Library/Python/3.9/bin:/opt/homebrew/bin:$PATH"
1. sudo chown -R $(whoami) /opt/homebrew
1. `brew analytics off`
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
1. Install node lts
  - export N_PREFIX=$HOME/.n
  - export PATH=$N_PREFIX/bin:$PATH
  - LTS with `n install lts latest 16`
1. Setup ZSH (zsh4humans, dotfiles, powerlevel10k)
  - zsh4humans
  - zoxide `echo 'eval "$(zoxide init zsh)"' >> ~/.zshrc
  - ZSH themes
    - Pure
    - https://github.com/Powerlevel9k/powerlevel9k/wiki/Show-Off-Your-Config
    - https://github.com/ohmyzsh/ohmyzsh/wiki/Themes
  - Aliases
    - https://github.com/zimfw/utility/blob/master/init.zsh
    - https://github.com/zimfw/git/blob/master/init.zsh
    - https://github.com/ericboehs/dotfiles/blob/master/.zsh/abbreviations.zsh
    - https://github.com/ohmyzsh/ohmyzsh/wiki/Cheatsheet
    - https://github.com/ohmyzsh/ohmyzsh/discussions/10591
  - obsolete
    - fzf `$(brew --prefix)/opt/fzf/install`
    - powerlevel10k `echo "source $(brew --prefix)/opt/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc`
1. Setup VIM (NeoVIM, 8+ Extensions)
  - Vimrc https://github.com/amix/vimrc#how-to-install-the-basic-version
  - Pathogen/Vundle/Vim-plug or native modules https://shapeshed.com/vim-packages/ https://vimhelp.org/repeat.txt.html#packages
    - https://medium.com/@paulodiovani/installing-vim-8-plugins-with-the-native-pack-system-39b71c351fea
    - https://dev.to/sabrinagannon/moving-to-native-vim-plugin-management-1hpa
    - https://medium.com/@huntie/10-essential-vim-plugins-for-2018-39957190b7a9
    - https://github.com/editorconfig/editorconfig-vim
  - Neovim
  - Themes
    - https://raw.githubusercontent.com/GertjanReynaert/cobalt2-vim-theme/master/colors/cobalt2.vim
    - https://raw.githubusercontent.com/connorholyday/vim-snazzy/master/colors/snazzy.vim
1. Setup Hyper
  - `hyper install hyper-snazzy`
1. Unhide Sound icon in Statusbar
1. Disable audio bell on Terminal profile
1. Remap Esc-Caps Lock for internal keyboard
1. macFUSE: ext2, ext4
1. Dock positions
1. Show HomeFolder, Harddrive in Finder
1. Configure Hot Corners
1. Start ScrollReverser, Rectangle, Raycast
1. Start Android Studio
  - Install SDK, Platform Tools
1. Configure VSCode
  - Settings
  - Themes
  - Extensions
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
  - cp torrc /opt/homebrew/etc/tor/torrc
  - brew services restart tor
1. Add printer drivers
  - https://support.apple.com/kb/DL1888?locale=en_US
1. Allow Canon EOS Camera for Slack, Teams, Zoom
  - Run EOS Utility v2! Installer
  - Run EOS Webcam Pro Installer
1. Download GooseVPN `wget https://appup.goosevpn.com/GOOSE_VPN.dmg`
1. Configure System
  - https://github.com/charlax/dotfiles/blob/master/install/install-apps-all.sh
  - https://git.herrbischoff.com/awesome-command-line-apps/about/#macos
  - https://github.com/geerlingguy/dotfiles
  - https://github.com/mathiasbynens/dotfiles
  - https://github.com/kalkayan/dotfiles
  - https://github.com/kalkayan/dotfiles/blob/main/.aliases#L69
  - https://wiki.nikitavoloboev.xyz/unix/dotfiles
  - https://github.com/mitchellh/nixos-config
1. Download Glorious Software
  - https://downloads.gloriousgamingservices.com/download/SETUP_FW_MAC_OS_UPDATER.zip
1. Download Altus
  - https://github.com/amanharwara/altus/releases
1. Run `aider-install`