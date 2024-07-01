# Buggo by micheal-r
Buggo is a package for debugging discord.js. Forked from Dokdo.

## Installation
```bash
cd your-bot/node_modules
git clone https://github.com/micheal-r/buggo
```

### Notes

Buggo requires a folder to store data in, like logs and errors. The default value is `your-bot/data/logs`, change this is your buggo config file located at `node_modules/buggo/buggo-config.json`.

## Customisation
Buggo is customizable by going to `node_modules/buggo/buggo-config.json` and changing the variables like the emoji's etc.
#### Example values

| Setting    | Value                                                              |
| ---------- | ------------------------------------------------------------------ |
| Emojis | <"emoji-name":"emoji-id"> |
| Color | ![#2B2D31](https://via.placeholder.com/10/2B2D31?text=+) #2B2D31 |
| Enabled | true|