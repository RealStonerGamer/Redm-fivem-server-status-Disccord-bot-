# Redm-fivem-server-status-Disccord-bot-
Redm /fivem server status Disccord bot 

translated to Eng



originalcode by : Robin-RoqueDEV https://github.com/RoqueDEV/fivemserverstatus



## Setup

```
URL_SERVER - base url for fiveM server e.g. http://127.0.0.1:3501 (don't end with /)
LOG_LEVEL - Int of enum 0-4 specifying level of logs to display with 4 as no logs
BOT_TOKEN - Discord bot token
CHANNEL_ID - channel id for updates to be pushed to
MESSAGE_ID - message id of previous update to edit (not required)
SUGGESTION_CHANNEL - channel to create suggestion embeds in
BUG_CHANNEL - channel to recieve bug reports
BUG_LOG_CHANNEL - channel to log bug reports
LOG_CHANNEL - channel to log status changes
```

##Running
1. `npm i`
2. `npm start` or `node ./index.js`

## Commands
1. `$FTstatus` `<Message>` to add a warning message in the server status embed.
2. `$FTstatus` `clear` to clear the warning message.



Credits
Roque https://github.com/RoqueDEV
Douile https://github.com/Douile
drazero https://github.com/draZer0
Robin-RoqueDEV https://github.com/RoqueDEV/fivemserverstatus
