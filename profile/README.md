<h1 align="center" style="padding-top: 60px;padding-bottom: 40px;">
    <a href="https://electerm.org">
        <img src="https://github.com/electerm/electerm-resource/raw/master/static/images/electerm.png", alt="" />
    </a>
</h1>

# electerm

<p>
 <a href="https://www.star-history.com/electerm/electerm"><img src="https://api.star-history.com/badge?repo=electerm/electerm" alt="Star History Rank" /></a>
</p>

Open-sourced terminal/ssh/sftp/telnet/serialport/RDP/VNC/Spice/ftp client(linux, mac, win).

<div align="center">
  <img src="https://github.com/electerm/electerm-resource/raw/master/static/images/electerm.gif", alt="" />
</div>

## Projects

| Project | Description |
|---------|-------------|
| [electerm](https://github.com/electerm/electerm) | Desktop app (Linux, Mac, Windows) |
| [electerm-web](https://github.com/electerm/electerm-web) | Browser-based version (including mobile) |
| [electerm-web-docker](https://github.com/electerm/electerm-web-docker) | Docker image for electerm-web |
| [electerm online](https://cloud.electerm.org) | Public free online app |
| [electerm demo](https://demo.electerm.org) | Online demo |
| [electerm-locales](https://github.com/electerm/electerm-locales) | Multi-language support |
| [electerm AI](https://ai.electerm.org) | Free AI for electerm users |
| [electerm-android](https://github.com/electerm/electerm-android) | Android app |

## Features

- Terminal/file manager, ssh/sftp/ftp/telnet/serialport/RDP/VNC/Spice client
- Global hotkey to toggle window visibility (default `ctrl + 2`)
- Multi-platform (Linux, Mac, Windows) with multi-language support
- Double-click editing of remote files
- Auth with publicKey + password
- Zmodem (rz, sz) and [Trzsz](https://github.com/trzsz/trzsz) support, compatible with tmux
- SSH tunnel support
- Transparent window (Mac, Win), terminal background image
- Global/session proxy
- Quick commands and UI/terminal theming
- Sync bookmarks/themes/quick commands to github/gitee gist/webdav/custom server/electerm cloud
- Quick input to one or all terminals
- AI assistant integration (DeepSeek, OpenAI, and other AI APIs)
- MCP (Model Context Protocol) widget for AI assistants and external tools
- Deep link support (e.g. `ssh://user@host:22`, `telnet://192.168.2.31:34554`)

## Install

```bash
# Mac
brew install --cask electerm

# Snap
sudo snap install electerm --classic

# Windows (winget)
winget install electerm.electerm

# npm
npm i -g electerm
```

Also available on [Microsoft Store](https://www.microsoft.com/store/apps/9NCN7272GTFF), [SourceForge](https://sourceforge.net/projects/electerm.mirror/files/), and [GitHub Releases](https://github.com/electerm/electerm/releases). Some Linux distros have it in their default app store.

### Linux package repositories

Prefer installing from your system's package manager? electerm provides dedicated apt and yum/dnf repositories:

- **deb (Debian/Ubuntu):** [https://repos.electerm.org/deb/](https://repos.electerm.org/deb/)
- **rpm (Fedora/RHEL/CentOS/openSUSE):** [https://repos.electerm.org/rpm/](https://repos.electerm.org/rpm/)

## Links

- 🌐 [Homepage](https://electerm.org)
- 📖 [Wiki](https://github.com/electerm/electerm/wiki)
- 💬 [Discussions](https://github.com/electerm/electerm/discussions) · [Discord](https://discord.gg/s4wv4N4e)
- 🐛 [Issues](https://github.com/electerm/electerm/issues)
- 📹 [Video guide](https://electerm.org/videos)
- 📋 [Changelog](https://github.com/electerm/electerm/releases)

## Sponsor

- [GitHub Sponsors](https://github.com/sponsors/electerm)
- [Ko-fi](https://ko-fi.com/zhaoxudong)

## License

MIT
