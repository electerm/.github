<h1 align="center" style="padding-top: 60px;padding-bottom: 40px;">
    <a href="https://electerm.org">
        <img src="https://github.com/electerm/electerm-resource/raw/master/static/images/electerm.png", alt="" />
    </a>
</h1>

# electerm

Open-sourced terminal/ssh/sftp/telnet/serialport/RDP/VNC/Spice/ftp client(linux, mac, win).

<div align="center">
  <img src="https://github.com/electerm/electerm-resource/raw/master/static/images/electerm.gif", alt="" />
</div>

## Related projects

- [electerm](https://github.com/electerm/electerm) - the main desktop app
- [electerm-web](https://github.com/electerm/electerm-web) - browser-based version(including mobile)
- [electerm-web-docker](https://github.com/electerm/electerm-web-docker) - docker image for electerm-web
- [electerm online](https://cloud.electerm.org) - a public free online app
- [electerm demo](https://demo.electerm.org) - an online demo

## Features

- Works as a terminal/file manager or ssh/sftp/ftp/telnet/serialport/RDP/VNC/Spice client
- Global hotkey to toggle window visibility(default is `ctrl + 2`)
- Multi platform(linux, mac, win)
- Multi-language support([electerm-locales](https://github.com/electerm/electerm-locales), contributions/fixes welcome)
- Double click to directly edit (small) remote files
- Auth with publicKey + password
- Support Zmodem(rz, sz)
- Support ssh tunnel
- Support [Trzsz](https://github.com/trzsz/trzsz)(trz/tsz), similar to rz/sz, and compatible with tmux
- Transparent window(Mac, win)
- Terminal background image
- Global/session proxy
- Quick commands
- UI/terminal theme
- Sync bookmarks/themes/quick commands to github/gitee secret gist/webdav/custom server/electerm cloud
- Quick input to one or all terminals
- AI assistant integration supporting DeepSeek, OpenAI and other AI APIs
- MCP(Model Context Protocol) widget for AI assistants and external tools
- Deep link support(e.g. `telnet://192.168.2.31:34554` or `ssh://user@host:22`)
- Command line usage: check [wiki](https://github.com/electerm/electerm/wiki/Command-line-usage)

## Download

- [Homepage](https://electerm.org)
- [sourceforge](https://sourceforge.net/projects/electerm.mirror/files/)
- [github releases](https://github.com/electerm/electerm/releases)

## Install

- For Mac user: `brew install --cask electerm`
- With snap: `sudo snap install electerm --classic`
- For some Linux distribution, you can find it from OS default App store(Ubuntu, Deepin, Mint...).
- For some linux OS, the `rpm`, `deb`, or `snap` release may not work, you can try the `tar.gz` or `.appImage` release.
- For Windows users, you can install it from [windows store](https://www.microsoft.com/store/apps/9NCN7272GTFF), command-line installer [winget](https://github.com/microsoft/winget-cli) and [scoop](https://github.com/lukesampson/scoop) is also recommended:

```powershell
# winget https://github.com/microsoft/winget-cli
winget install electerm.electerm

# scoop https://github.com/lukesampson/scoop
scoop bucket add dorado https://github.com/chawyehsu/dorado
scoop install dorado/electerm
```

- Install from npm

```bash
npm i -g electerm
```

## Upgrade

- Auto upgrade: When a new version is released, you will get an upgrade notification after you start electerm again. You can then click the upgrade button to upgrade.
- Download: Just download the latest edition, reinstall.
- Npm: If you install from npm, just run `npm i -g electerm` again.
- If use Snap or some other distribution system, these systems may provide upgrades.

## Known issues & Troubleshoot

- [Known issues](https://github.com/electerm/electerm/wiki/Know-issues)
- [Troubleshoot](https://github.com/electerm/electerm/wiki/Troubleshoot)

## Discussion

- [Discord](https://discord.gg/s4wv4N4e)
- [Discussion board](https://github.com/electerm/electerm/discussions)

## Support

Would love to hear from you, please tell me what you think, [submit an issue](https://github.com/electerm/electerm/issues), [Start a new discussion](https://github.com/electerm/electerm/discussions/new), [create/fix language files](https://github.com/electerm/electerm-locales) or create pull requests, all welcome.

## Sponsor this project

- [GitHub Sponsors](https://github.com/sponsors/electerm)
- [Ko-fi](https://ko-fi.com/zhaoxudong)

## Video guide

[Video guide](https://electerm.org/videos)

## Change log

Visit [Releases](https://github.com/electerm/electerm/releases).

## License

MIT
