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

### &#10003; Autossh [![](https://images.microbadger.com/badges/version/odinuge/hassio-addon-autossh-armhf.svg)](https://microbadger.com/images/odinuge/hassio-addon-autossh-armhf "Get your own version badge on microbadger.com")
Simple autossh addon. The addon creates a ssh keypair, and uses it
to connect to to the given host. The public key can be found in the
log after the first startup.

Remember to set `GatewayPorts clientspecified` in sshd-config if you
would like to open ports on other interfaces than localhost.

**IMPORTANT**: If you set `GatewayPorts yes`, all forwarded ports will
listen on all interfaces, `0.0.0.0`. `GatewayPorts clientspecified`
is preferable.

### Licence
MIT (c) DSR!

[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2022.svg
[license-shield]: https://img.shields.io/github/license/hassio-addons/repository.svg
[discord-shield]: https://img.shields.io/discord/478094546522079232.svg
[discord]: https://discord.me/hassioaddons
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io?u=xchwarze
