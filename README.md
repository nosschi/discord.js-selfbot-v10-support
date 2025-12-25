## abt

- ts shi is a fork of https://github.com/aiko-chan-ai/discord.js-selfbot-v13, ts nigga despreciated that 🤣🤣🤣
- discord api v10 support, not v9


## features (user)
- [x] message
- [x] clientuser: status, activity, remoteauth, etc.
- [x] guild: fetch members, join / leave, top emojis, etc.
- [x] interactions: slash commands, buttons, menu, modal.
- [x] captcha & totp handler
- [x] documentation
- [x] voice & video

## installation

> **node.js 20.18.0 or newer is required**

```sh-session
npm install nosschi/discord.js-selfbot-v10-support
```

## example

```js
const { Client } = require('discord.js-selfbot-v13');
const client = new Client();

client.on('ready', async () => {
  console.log(`${client.user.username} is ready!`);
})

client.login('token');
```


## contributing

- original lib: https://github.com/discordjs/discord.js
- forked from: https://github.com/aiko-chan-ai/discord.js-selfbot-v13 (despreciated) 

@nosschi :3
