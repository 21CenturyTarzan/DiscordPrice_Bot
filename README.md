# CoinGecko-Discord-Bot
CoinGeckoBot Discord Crypto Price Bot


[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/cleot/CoinGecko-Discord-Bot)



Deploy to Heroku:

1. Fork Repo
2. Create new app on heroku
3. Connect to Github
4. Select Repo
5. Configure Config Vars in settings
6. Deploy
7. Start worker (Resources)


HEROKU Example Config Vars:

- DISCORD_TOKEN=YOUR_DISCORD_BOT_TOKEN
- REFRESH_TIMER=60
- CONTRACT=0xdac17f958d2ee523a2206206994597c13d831ec7
- CHAIN=ethereum # https://api.coingecko.com/api/v3/asset_platforms
- CURRENCY=usd
- NAME=USDT

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
