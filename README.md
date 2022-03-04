# Valorant store checker - Discord Bot (BETA)
Discord bot that shows your daily store offer without opening the VALORANT base game by using the Ingame API.
written using Python and the [Pycord](https://github.com/Pycord-Development/pycord) library <br>

## Screenshot
* Store

![store](https://github.com/TehHatrix/nash-discordbotvalorant/blob/main/README/Store.png?raw=true)
<br>

* Notify skin

![notify](https://github.com/TehHatrix/nash-discordbotvalorant/blob/main/README/Notify.png?raw=true)

* NightMarket

![nightmarket](https://github.com/TehHatrix/nash-discordbotvalorant/blob/main/README/NightMarket.png?raw=true)

* Checking Valorant Points

![point](https://github.com/TehHatrix/nash-discordbotvalorant/blob/main/README/Point.png?raw=true)

## Installations

* [Python 3.8+](https://www.python.org/downloads/)

* Install requirements

* Create the [discord bot](https://discord.com/developers/applications) and invite bot to server with scope `applications.commands`

* Clone/[Download](https://github.com/staciax/ValorantStoreChecker-discord-bot/archive/refs/heads/master.zip)

```
pip install -r requirements.txt
```

```
# manual install package

pip install pillow
pip install py-cord==2.0.0b4
pip install requests
```

* Store discord bot token in [config.json](https://github.com/staciax/ValorantStoreChecker-discord-bot/blob/master/config.json)
```
"TOKEN": "PUT YOUR DISCORD BOT TOKEN"
```
* Run the bot
```
python bot.py
```

## Usage

| Command                       | Action                                                                                                     |
| :---------------------------- | :--------------------------------------------------------------------------------------------------------- |
| `store`  | Shows your daily store |
| `point`  | Shows your valorant point |
| `login`  | Log in with your Riot acoount |
| `logout`  | Logout your Riot acoount |
| `2fa`  | Enter your 2FA Code |
| `notify`  | Set an notify for when a particular skin is in your store |
| `notifys`  | Shows all your skin notify |
| `notify_mode`  | Change notify mode `spectified skin` or `all skin` |
| `nightmarket`  | Shows your nightmarket |

## Special thanks

### [Valorant Client API](https://github.com/RumbleMike/ValorantClientAPI) by [RumbleMike](https://github.com/RumbleMike)
for providing a great API about Valorant!

### [Valorant-API.com](https://valorant-api.com/)
for every skin names and images!

### [Discord - Valorant App Developer ](https://discord.gg/a9yzrw3KAm) by [MikeValorantLeaks](https://github.com/RumbleMike)
developer community for valorant api
