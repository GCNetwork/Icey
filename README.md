<div align="center">

<kbd>
<img style="border-radius:50%" height="150px" src="">
</kbd>

<h1>Icey</h1>

<h3>An Alpha Proxy Developed By GC Network to bypass blocking filters</h3>

<p>Surf without web filters or restrictions. Icey is a service dedicated to protecting your freedom from censorship.
Read the documentation below to find out more</p>


<p align="center">
<a href="https://repl.it/github/Nebelung/Icey"><img height="30px" src="https://raw.githubusercontent.com/FogNetwork/Tsunami/main/deploy/replit2.svg"><img></a>
</p>

## Documentation

- [Overview](#overview)
  - [Supported Sites](#supported-sites)
  - [Features](#features)
  - [Pages](#pages)
- [Setup](#setup)
  - [Locally](#locally)
  - [Deploy](#deploy)
  - [Proxies](#proxies)
  - [Configuration](#configuration)
- [Support](#support)
  - [FAQ](#faq)
  - [Contact](#contact)
- [More](#more)
  - [Proxy Sources](#proxy-sources)
  - [Credits](#credits)
  - [Contributing](#contributing)

## Overview

### Supported Sites

- google.com
- discord.com
- youtube.com
- invidio.us
- 1v1.lol
- schoolcheats.net
- sealcentral.gq
- lookmovie.io

### Features

- All the best proxies
- Tab cloaking and other cool features
- Basic auth
- Customizable CSS

## Pages

- `/` Homepage
- `/index2`Terms
- `/index3`Credits
- `/index4`Settings
- `/404` 404 Error

## Setup

### Locally

```sh
git clone https://github.com/GCNetwork/Icey

cd Icey

npm install

npm start
```

### Deploy

Click one of the buttons above and follow the steps

### Proxies

Some of the proxies on Tsunami are hosted on subdomains, deploy the correct proxy for Tsunami to work

Palladium and Corrosion are hosted locally, so you don't need a subdomain

[Locally (Palladium)](https://github.com/FogNetwork/Palladium)

[Locally (Corrosion)](https://github.com/titaniumnetwork-dev/Corrosion)

### Configuration

**config.json**

```json
{
    "port": "8080",
    "lite": "false",
    "auth": "false",
    "username": "user",
    "password": "secret"
}
```

`"port": "8080"` Changes the port 

`"username"` Username for authentication

`"password"` Password for authentication

**/public/js/go.js**

```js
var palladiumproxy = window.location.protocol + "//" + window.location.hostname + "/palladium/gateway?url="

var corrosionproxy = window.location.protocol + "//" + window.location.hostname + "/corrosion/gateway?url="

```
`palladiumproxy` Location for Palladium proxy

`corrosionproxy` Location for Corrosion proxy

Custom Proxy Example:

```js
var palladiumproxy = "https://example.com/palladium/"
```

## Support

### FAQ

**How can I get new domains?**

We have a couple (Official) Mirrored links you may use. Eventually we will get more ways to get domains for you people.

Mirrored:

https://www.iceyzero.cf
https://www.iceywork.gq

**Captcha not working/issues**

I suggest you use the QR Code scanner to login, Much faster and can be used via the Discord App!

**Why is Discord not working properly?**

Try using Corrosion. Refreshing the page might help,

### Contact

Cone - [Cone#3280](https://discord.com/users/452256800897761291)

## More

### Proxy Sources

[Palladium](https://github.com/FogNetwork/Palladium)

[Corrosion](https://github.com/titaniumnetwork-dev/Corrosion)

[Modified Corrosion](https://github.com/BinBashBanana/Corrosion-Heroku)

[Alloy](https://github.com/titaniumnetwork-dev/alloy) (Not Used)

[SystemYA](https://github.com/sysce/proxy) (Not Used)

[Via](https://github.com/hypothesis/via) (Not Used)

[Node Unblocker](https://github.com/nfriedly/node-unblocker) (Not Used)

[Powermouse](https://github.com/titaniumnetwork-dev/powermouse) (Not Used)

### Credits

[Cone](https://github.com/Page07) - Owner and Main Developer

[DamoGames](https://github.com/DamoGamesYT) - Developer

[Degen](https://github.com/Degenerate0001) - Helper

[EnderKingJ](https://github.com/EnderKingJ) - Developer

[Nebelung](https://github.com/Nebelung) - Proxy Developer

### Contributing

Special Thanks Nebelung, Inspiration for Icey and all his wonderful help.
