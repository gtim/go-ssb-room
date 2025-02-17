# Go-SSB Room
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fssb-ngi-pointer%2Fgo-ssb-room.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fssb-ngi-pointer%2Fgo-ssb-room?ref=badge_shield)

This repository contains code for a [Secure Scuttlebutt](https://ssb.nz) [Room (v1+v2) server](https://github.com/ssb-ngi-pointer/rooms2), written in Go.

It includes:
* secret-handshake+boxstream network transport, sometimes referred to as SHS, using [secretstream](https://github.com/cryptoscope/secretstream)
* muxrpc handlers for tunneling connections
* a fully embedded HTTP server & HTML frontend, for administering the room

![](./docs/images/screenshot.png)

## :star: Features

* Rooms v1 (`tunnel.connect`, `tunnel.endpoints`, etc.)
* User management (allow- & denylisting + moderator & administrator roles), all administered via the web dashboard
* Multiple [privacy modes](https://ssb-ngi-pointer.github.io/rooms2/#privacy-modes)
* [Sign-in with SSB](https://ssb-ngi-pointer.github.io/ssb-http-auth-spec/)
* [HTTP Invites](https://github.com/ssb-ngi-pointer/ssb-http-invite-spec)
* Alias management

## :rocket: Deployment

If you want to deploy a room server yourself, follow our [deployment.md](./docs/deployment.md) docs.

## :wrench: Development

For an in-depth codebase walkthrough, see the [development.md](./docs/development.md) file in the `docs` folder of this repository.

## :people_holding_hands: Authors

* [cryptix](https://github.com/cryptix) (`@p13zSAiOpguI9nsawkGijsnMfWmFd5rlUNpzekEE+vI=.ed25519`)
* [staltz](https://github.com/staltz)
* [cblgh](https://github.com/cblgh)

## License

MIT

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fssb-ngi-pointer%2Fgo-ssb-room.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fssb-ngi-pointer%2Fgo-ssb-room?ref=badge_large)