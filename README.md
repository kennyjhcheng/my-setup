# My Mac Setup

This repository contains my personal Mac setup configuration and documentation of the tools I use.

## Terminal & Shell

- [iTerm2](https://iterm2.com/) - Terminal emulator
  - Configuration: `iterm-profile.json`
- [Oh My Zsh](https://ohmyz.sh/) - Framework for managing Zsh configuration
  - Configuration: `.zshrc`
- [Powerlevel10k](https://github.com/romkatv/powerlevel10k) - Zsh theme
- [Homebrew](https://brew.sh/) - Package manager for macOS

## Development Tools

- [Node.js](https://nodejs.org/) - JavaScript runtime
- [NVM](https://github.com/nvm-sh/nvm) - Node Version Manager
- [Git](https://git-scm.com/) - Version control system
  - Custom aliases configured

## Code Editors

- [Visual Studio Code](https://code.visualstudio.com/) - Code editor
- [Cursor](https://cursor.sh/) - AI-powered code editor

## Web Browsers

- [Chrome](https://www.google.com/chrome/) - Web browser
- [Arc](https://arc.net/) - Modern web browser
- [Firefox](https://www.mozilla.org/firefox/) - Web browser

## Productivity & Entertainment

- [Todoist](https://todoist.com/) - Task management
- [Spotify](https://www.spotify.com/) - Music streaming
- [Notion](https://www.notion.so/) - Note-taking and organization
- [Obsidian](https://obsidian.md/) - Note-taking and knowledge management
- [Yomu](https://apps.apple.com/us/app/yomu-pdf-reader/id489909020) - PDF reader

## Media & Utilities

- [VLC](https://www.videolan.org/vlc/) - Media player
- [uTorrent](https://www.utorrent.com/) - BitTorrent client
- [OBS Studio](https://obsproject.com/) - Screen recording and streaming

## Setup Instructions

1. Install Homebrew:
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2. Install iTerm2:
```bash
brew install --cask iterm2
```

3. Install Oh My Zsh:
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

4. Install Powerlevel10k:
```bash
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

5. Install Node.js and NVM:
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
nvm install node  # Installs the latest version
```

6. Install other applications via Homebrew:
```bash
brew install --cask visual-studio-code
brew install --cask spotify
brew install --cask vlc
brew install --cask notion
brew install --cask obsidian
brew install --cask obs
brew install --cask firefox
brew install --cask arc
```

## Configuration Files

- `iterm-profile.json` - iTerm2 profile configuration
- `.zshrc` - Zsh configuration file
- Git aliases are configured in `.gitconfig`