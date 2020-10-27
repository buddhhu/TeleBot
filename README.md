## 👑Creator👨‍🔧

*LovedeepViRk

# DeepTeleBot - Telegram UserBot

# <p align="left"><a href="https://github.com/Lovedeep-ViRk/DeepTeleBot"><img src="https://github-readme-stats.vercel.app/api/pin?username=Lovedeep-ViRk&show_icons=true&theme=dark&hide_border=true&repo=DeepTeleBot"></a></p><p align="centre"><a href="https://t.me/DeepTeleBotHelpChat"> <img src="https://img.shields.io/badge/telegram-Support_Group-blue?style=social&logo=telegram" alt="Support" /></a><a href="https://github.com/Lovedeep-ViRk/DeepTeleBot/stargazers"><img src="https://img.shields.io/github/stars/Lovedeep-ViRk/DeepTeleBot?style=social"></a><a href="https://github.com/Lovedeep-ViRk/DeepTeleBot/fork"><img src="https://img.shields.io/github/forks/Lovedeep-ViRk/DeepTeleBot?label=Fork&logoColor=blue&style=social"></a>	<a href="https://github.com/Lovedeep-ViRk/DeepTeleBot"><img src="https://img.shields.io/github/last-commit/Lovedeep-ViRk/DeepTeleBot?style=flat-square"></a></p>
    
## The Easier Way to install

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/xditya/TeleBot)

## Support
Join [TeleBot Support group](https://t.me/TeleBotSupport) for updates and new plugin suggestions.
Do fork and star the repo 

### Session String 
<a href="https://telebot-sessionstring-generator.xditya.repl.run/" target="_blank"><img src="https://img.shields.io/badge/run-string__session.py-red?style=for-the-badge&logo=repl.it" alt="generate_string" /></a>

### The Normal Way

Simply clone the repository and run the main file:
```sh
git clone https://github.com/xditya/TeleBot
cd TeleBot
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
# <Create local_config.py with variables as given below>
python3 -m userbot
```

An example `local_config.py` file could be:

**Not All of the variables are mandatory**

__The Userbot should work by setting only the first two variables__

```python3
from heroku_config import Var

class Development(Var):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
```

**Heroku Configuration**
Simply just leave the Config as it is.

**Local Configuration**
Check [Line 111](https://github.com/Total-Noob-69/X-tra-Telegram/blob/master/userbot/uniborgConfig.py#L111) and start adding your vars there.
Fortunately there are no Mandatory vars for the UniBorg Support Config.

## Mandatory Vars

- Only two of the environment variables are mandatory.
- This is because of `telethon.errors.rpc_error_list.ApiIdPublishedFloodError`
    - `APP_ID`:   You can get this value from https://my.telegram.org
    - `API_HASH`:   You can get this value from https://my.telegram.org
- The userbot will not work without setting the mandatory vars.

# Disclaimer
```
/**
    	Improper use may lead to ban.
    	I am not responsible if you misuse this bot.
	This bot is just for managing groups more effectively and having some fun
	with your telegram account.
	No one is responsible for your actions.
	If you spammed and got reported again and again, 
	and, at last got your account banned, and you
	point your fingers at me, I'll be rolling on the floor laughing at you.
/**
```

