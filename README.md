[![Maintainability](https://api.codeclimate.com/v1/badges/347e0974b306643c3f82/maintainability)](https://codeclimate.com/github/ks00908/doot-doot/maintainability) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)  [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![python3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://img.shields.io/badge/python-3.7-blue.svg)
# Doot-Doot
A Discord bot that play sound effects in voice channel on command.
Now with Additional Doot

## Installation

### Prerequisites:
  * Python 3.7
  * Discord.py rewrite library
  * Discord bot account with token (obtainable through the [Discord Developer Portal](https://discordapp.com/developers/applications/))
  * aiohttp library
  
### Starting bot:
  1. Install pre-requisites
  2. Copy bot files to location where you want to store them
  3. Replace 'token' in main.py with token
  4. Open CMD/PowerShell/Terminal and navigate to folder with bot files
  5. Type ``python main.py`` (if it will not work try ``python3.7 main.py``
  6. Wait until bot logs in to Discord
  
  
## Adding new sound effects
Replace command_syntax and file_name respectively with: command used to play sound and filename of sound
### Syntax
```py
    @commands.command()
    @commands.guild_only()
    async def command_syntax(self, ctx):
        """command_description"""
        await play_file(ctx, "sounds/file_name.mp3")
```
## Attributions

Bot and support server images were created by Freepik from www.flaticon.com and are under Creative Commons BY 3.0 licence
