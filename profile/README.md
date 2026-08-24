<h1 align="center" style="padding-top: 60px;padding-bottom: 40px;">
    <a href="https://electerm.org">
        <img src="https://github.com/electerm/electerm-resource/raw/master/static/images/electerm.png", alt="" />
    </a>
</h1>

[![GitHub version](https://badgers.space/github/release/electerm/electerm?corner_radius=m)](https://github.com/electerm/electerm/releases)
[![Build Status](https://github.com/electerm/electerm/actions/workflows/mac-test-1.yml/badge.svg)](https://github.com/electerm/electerm/actions)
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/electerm/electerm/blob/master/LICENSE)
[![GitHub Sponsors](https://img.shields.io/github/sponsors/electerm?label=Sponsors)](https://github.com/sponsors/electerm)
[![star](https://atomgit.com/electerm/electerm/star/badge.svg)](https://atomgit.com/electerm/electerm)

Open-sourced terminal/ssh/sftp/telnet/serialport/RDP/VNC/Spice/ftp client family(Linux, Mac, Windows, Android, HarmonyOS, and web).

<p>
  <a href="https://electerm.org">Homepage / Downloads</a> ·
  <a href="https://theme.electerm.org">Theme</a> ·
  <a href="https://github.com/electerm/electerm-web-docker">Docker</a> ·
  <a href="https://demo.electerm.org">Online demo</a> ·
  <a href="https://github.com/electerm/electerm-android">Android</a> ·
  <a href="https://github.com/electerm/electerm-harmony">HarmonyOS</a> ·
  <a href="https://appgallery.huawei.com/app/detail?id=org.electerm.electerm">Huawei AppGallery</a> ·
  <a href="https://www.microsoft.com/store/apps/9NCN7272GTFF">Microsoft Store</a> ·
  <a href="https://snapcraft.io/electerm">Snap Store</a> ·
  <a href="https://repos.electerm.org/deb">deb repo</a> ·
  <a href="https://repos.electerm.org/rpm">rpm repo</a>
</p>

<div>🌐 <strong><a href="https://cloud.electerm.org">electerm online</a></strong> — Public free online electerm app</div>
<div>🤖 <strong><a href="https://ai.electerm.org">electerm AI</a></strong> — Free AI for electerm users</div>
<div>💻 <strong><a href="https://github.com/electerm/electerm-web">electerm-web</a></strong> — Web app version running in browser (including mobile device)</div>
<div>🎨 <strong><a href="https://theme.electerm.org">electerm theme</a></strong> — Create/share themes with live preview and AI creation</div>
<div>📱 <strong><a href="https://github.com/electerm/electerm-android">electerm-android</a></strong> — Android app</div>
<div>🪷 <strong><a href="https://github.com/electerm/electerm-harmony">electerm-harmony</a></strong> — HarmonyOS app (available on <a href="https://appgallery.huawei.com/app/detail?id=org.electerm.electerm">Huawei AppGallery</a>)</div>

<div align="center">
    <img src="https://github.com/electerm/electerm-resource/raw/master/static/images/electerm-banner-1.jpg", alt="" />
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
| [electerm theme](https://theme.electerm.org) | Create/share theme site with live preview and AI creation |
| [electerm-android](https://github.com/electerm/electerm-android) | Android app |
| [electerm-harmony](https://github.com/electerm/electerm-harmony) | HarmonyOS app (available on [Huawei AppGallery](https://appgallery.huawei.com/app/detail?id=org.electerm.electerm)) |

## Features

- Terminal/file manager, ssh/sftp/ftp/telnet/serialport/RDP/VNC/Spice client
- Multi-platform (Linux, Mac, Windows, Android, HarmonyOS) with multi-language support
- Global hotkey to toggle window visibility (default `ctrl + 2`)
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

## Install (Desktop)

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
