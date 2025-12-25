## About

<strong>Welcome to `discord.js-selfbot-v13@v3.7`, based on `discord.js@13.17` and backport `discord.js@14.21.0`</strong>

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

> [!NOTE]
> **Node.js 20.18.0 or newer is required**

```sh-session
npm install discord.js-selfbot-v13@latest
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

## Get Token ?

- Based: [findByProps](https://discord.com/channels/603970300668805120/1085682686607249478/1085682686607249478)

<strong>Run code (Discord Console - [Ctrl + Shift + I])</strong>

```js
window.webpackChunkdiscord_app.push([
	[Symbol()],
	{},
	req => {
		if (!req.c) return;
		for (let m of Object.values(req.c)) {
			try {
				if (!m.exports || m.exports === window) continue;
				if (m.exports?.getToken) return copy(m.exports.getToken());
				for (let ex in m.exports) {
					if (m.exports?.[ex]?.getToken && m.exports[ex][Symbol.toStringTag] !== 'IntlMessagesProxy') return copy(m.exports[ex].getToken());
				}
			} catch {}
		}
	},
]);

window.webpackChunkdiscord_app.pop();
console.log('%cWorked!', 'font-size: 50px');
console.log(`%cYou now have your token in the clipboard!`, 'font-size: 16px');
```

## Contributing

- original lib: https://github.com/discordjs/discord.js
- forked from: https://github.com/aiko-chan-ai/discord.js-selfbot-v13 (despreciated

@nosschi :3
