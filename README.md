# Clash of cars Price bot USD
Bot Clash of cars


[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/KiKoZl/clash-bot-price)

Bot created to be hosted to HEROKU, if you want to use the BOT in other HOST you need small modifications

Deploy to Heroku:

1. Fork Repo
2. Create new app on heroku
3. Connect to Github
4. Select Repo
5. Configure Config Vars in settings
6. Deploy
7. Start worker (Resources)


HEROKU Config Vars:

- DISCORD_TOKEN=YOUR_DISCORD_BOT_TOKEN
- REFRESH_TIMER=60
- CONTRACT=3aAYh35n81F8HPG2QBdE48aYdzGFj2fsLccg91X4AcRc
- CHAIN=solana # https://api.coingecko.com/api/v3/asset_platforms
- CURRENCY=usd
- NAME=CLASH

Discord bot setup:
1. Go to https://discord.com/developers/
2. Create new app "New Application"
3. Bot -> Add Bot
4. oAuth2 -> URL Generator-> SCOPES: "bot" -> BOT PERMISSIONS: "Administrator" -> GENERATED URL: Copy
5. Paste URL in new Tab -> select Discord server
6. Bot -> TOKEN: Copy -> use as "YOUR_DISCORD_BOT_TOKEN"
 





Sources:
- https://realpython.com/how-to-make-a-discord-bot-python/
- https://github.com/juliankoh/ribbon-discord-bot
- https://github.com/melenxyz/abracadabra-tvl-bot
