# Basic-Trades-DOCS-
https://discord.gg/6ASdpBjbDX / Basic#2142

# How to use:
```
1. Download the bot from the latest pin in #downloads
2. Extract the zip
3. Open & Edit config.json to add your cookie, proxy(s), bot token, and discord channels
4. Run the index-win.exe file (either in command prompt or by just double clicking it)
```

# How to get a Bot Token
```
> "bot_token"
1. Go to "https://discord.com/developers/applications" and login to your discord account
2. Press "New Application" and name the bot anything you'd like
3. Click the three bars at the top right of the screen and click the "Bot" tab
4. Create a bot and click "reveal token"
5. Copy the token and paste it into the string that follows "bot_token": in the config.json file
6. Go to the OAuth2 tab and click URL Generator 
7. Click the "bot" check box and click the "Administrator" box 
8. Then use the link created to invite the bot to your server
```

#Documentation
```
> "cookie"
Your RBX cookie

> "bot_token"
Your discord bot token

> "discordid"
YOUR discord ID

> "non-rotating"
When set to true the bot will use non-rotating proxies in the proxies.txt file

> "rotating"
When non-rotating is set to false the bot will use this rotating proxy for sending trades, the format is user:pass@hostname:port

> "key"
Your whitelist key

> "channelid"
The discord channel ID the bot will output something specific to

> "hex_color"
The hex color the discord embed will be (on regular outputs)

> "prefix"
The symbol, number, or phrase that will go before discord commands

> "error_channel"
The discord channel ID the bot will output errors

> "last_online"
The maximum amount of time, in seconds, from the last time a item owner was online to be queued
EX: If a madness owner was last online yesterday and "last_online" is set to 604800 (a week) they will be queued

> "send_delay"
The interval at which the bot will send trades (seconds)

> "request_timeout"
The maximum amount of time a request can take, in seconds, before being canceled

> "rstats_int"
The interval at which the bot will output runtime statistics (locally)
```
