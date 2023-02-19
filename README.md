# Spam Filter
A simple and efficient spam filter built to be used in discord bots made with any fork of [discord.py](https://github.com/Rapptz/discord.py)!

# Installation
You can use [pip](https://pip.pypa.io/en/stable/) to install this library.
```
pip install discordpy-antispam
```

# Usage
### Quickstart Guide
```py
from SpamFilter import AntiSpam

@bot.event
async def on_message(msg):
  spam_check = await AntiSpam().check(bot, msg.channel, msg.author)
```
