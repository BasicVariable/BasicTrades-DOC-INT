# Basic-Trades-DOCS-
https://discord.gg/6ASdpBjbDX / Basic#2142

# How to use:
```
1. Download the bot from the latest pin in #downloads
2. Extract the zip
3. Open & Edit config.json to the documentation below
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
> "auth" > "cookie"
Your RBX cookie

> "auth" > "key"
Your whitelist key

> "discord_bot" > "bot_token"
Your discord bot token

> "discord_bot" > "discordid"
YOUR discord ID

> "discord_bot" > "prefix"
The symbol, number, or phrase that will go before discord commands

> "discord_bot" > "channels" > "output"
The channel (as a channelid) where BT will post sent trades

> "discord_bot" > "channels" > "inv_changes"
The channel (as a channelid) where BT will post your account's inventory changes

> "discord_bot" > "channels" > "errors"
The channel (as a channelid) where BT will post errors that occur as a trade is being sent

> "sending" > "last_online"
The maximum amount of time, in number{d-m} format, from the last time a item owner was online to be queued
EX: If a madness owner was last online yesterday and "last_online" is set to 1w (a week) they will be queued

> "sending" > "send_delay"
The interval at which the bot will send trades (seconds)

> "sending" > "uuc_check" > "?"
Whether or not you'd like the check enabled

> "sending" > "uuc_check" > "scaninv_times"
The amount of pages of the person's inventory you'd like the bot to look through before stopping

> "sending" > "IPL_bypass"
Whether or not you'd like the bot to use the IP-Lock Bypass to send trades through your proxies

> "sending" > "DNS_to"
A list of people you'd like the bot to not send trades to
EX: [1, 2, 3, 4]

> "proxies.txt" (File)
The text file you'll place your proxies in:
EX:
user:pass@host:port
user:pass@host:port
user:pass@host:port

> "ms" (command)
The command used to start mass-sending to the owners of a specific item
EX:
&ms itemid [uaid,uaid,uaid,uaid]
```
