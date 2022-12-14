# Telegram-Bot-IoT
Chatbot Telegram can control IoT via API/endpoint

# Installation

## Connect To Project
* [`IoT Relay NodeMcu`](https://github.com/TierKun/IoT-Relay)

### other integration
* [`Whatsapp Bot`](https://github.com/TierKun/Whatsapp-Bot-IoT)

## Windows
* [`Download Node JS`](https://nodejs.org/en/download/)
* [`Download Git`](https://git-scm.com/download/win)


## Cloning this repo
```cmd
> git clone https://github.com/TierKun/Telegram-Bot-IoT
> cd Telegram-Bot-IoT
```

## Install the package
```cmd
> npm i
```

## Edit config file
Edit the required value in `config.json`. You can get the token blynk at [`blynk.cloud`](https://blynk.cloud/). And get bot token at [`@BotFather`](http://t.me/BotFather).
```json

  {
    "bot_token": "56xxxxx:jfrsjxxxxxxx", 
    "blynk_token": "VqR5Pyexxxxxxxxxxxxxxxxxx", 
    "blynk_server": "sgp1.blynk.cloud",
    "on_value": "1",
    "off_value": "0",
    "owner": "Tier Sinyo",
    "ownerLink": "https://t.me/TierkunDev",
    "version": "1.1.0",
  {

 ```

## Run the bot
```cmd
> npm start
```

## Stop the bot
```cmd
> ctrl + c 
```

# Thanks To
* [`Telegraf`](https://github.com/telegraf/telegraf)
* [`Blynk`](https://github.com/blynkkk/blynk-library)

