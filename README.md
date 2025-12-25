## About

- ts shi is a fork of https://github.com/aiko-chan-ai/discord.js-selfbot-v13, ts nigga despreciated that 🤣🤣🤣
- discord api v10 support, not v9


## Features 
- [x] Message
- [x] ClientUser: Status, Activity, RemoteAuth, etc.
- [X] Guild: Fetch Members, Join / Leave, Top emojis, etc.
- [X] Interactions: Slash Commands, Buttons, Menu, Modal.
- [X] Captcha & TOTP Handler
- [X] Documentation
- [x] Voice & Video

## Installation

> **node.js 20.18.0 or newer is required**

```sh-session
npm install nosschi/discord.js-selfbot-v10-support
```

## Example

```js
const { Client } = require('discord.js-selfbot-v13');
const client = new Client();

client.on('ready', async () => {
  console.log(`${client.user.username} is ready!`);
})

client.login('token');
```


## Contributing

- original lib: https://github.com/discordjs/discord.js
- forked from: https://github.com/aiko-chan-ai/discord.js-selfbot-v13 (despreciated) 

@nosschi :3
