# Home Assistant Community Add-ons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

[![Discord][discord-shield]][discord]
[![Community Forum][forum-shield]][forum]

## About

Home Assistant allows anyone to create add-on repositories to share their
add-ons for Home Assistant easily. This repository is one of those repositories,
providing extra Home Assistant add-ons for your installation.

The primary goal of this project is to provide you (as a Home Assistant user)
with additional, high quality, add-ons that allow you to take your automated
home to the next level.

## Installation

In general, there is no need to install this repository on your
Home Assistant instance. It is activated and added by Home Assistant
by default.

However, if the repository is missing on your setup, adding this add-ons
repository to your Home Assistant instance is pretty easy. In the
Home Assistant add-on store, a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/xchwarze/hassio-addons
```

## Add-ons provided by this repository

### &#10003; [Autossh][addon-autossh]

![Latest Version][autossh-version-shield]
![Supports armhf Architecture][autossh-armhf-shield]
![Supports armv7 Architecture][autossh-armv7-shield]
![Supports aarch64 Architecture][autossh-aarch64-shield]
![Supports amd64 Architecture][autossh-amd64-shield]
![Supports i386 Architecture][autossh-i386-shield]

Simple autossh addon. The addon creates a ssh keypair, and uses it
to connect to to the given host. The public key can be found in the
log after the first startup.

[:books: autossh add-on documentation][addon-doc-autossh]

## License

MIT License

Copyright (c) 2019-2022 DSR!

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2022.svg
[license-shield]: https://img.shields.io/github/license/hassio-addons/repository.svg
[discord-shield]: https://img.shields.io/discord/478094546522079232.svg
[discord]: https://discord.me/hassioaddons
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io?u=xchwarze
[addon-autossh]: https://github.com/xchwarze/addon-autossh/tree/v1.3.0
[addon-doc-autossh]: https://github.com/xchwarze/addon-autossh/blob/v1.3.0/README.md
[autossh-issue]: https://github.com/xchwarze/addon-autossh/issues
[autossh-version-shield]: https://img.shields.io/badge/version-v1.3.0-blue.svg
[autossh-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[autossh-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[autossh-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[autossh-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[autossh-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
