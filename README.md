# KABot

KABot is KA's personal Discord bot.

KABot can currently play music, deliver Kudos, and can be contributed to by anyone.
KABot is, for now, mostly boilerplate inspired from examples on the discord.py GitHub repository.

## Installation

1. Install the required dependency (discord.py with voice support)

```bash
root@localhost:~$ python3 -m pip install -U discord.py[voice]
```

2. Download the KABot from the repository, either through the Clone/Download button above, or by cloning it using git:
```bash
root@localhost:~$ git clone https://github.com/StormFireFox1/KABot.git
```

3. Setup envvars by modifying .env.example file to .env and setting all the necessary info. You can get the bot token and kudos channel ID by using the Developer portal

4. Start the script
```bash
root@localhost:~$ source .env & python main.py
```