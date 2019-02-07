# VideoScraperBot
A telegram bot that uses the command line utility [youtube-dl](https://github.com/rg3/youtube-dl/) to download videos from YouTube.com and other video sites.
This project is still under development

## Requirements 
* Python 3+
* [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)
  * Install via pip: pip install python-telegram-bot --upgrade
* [youtube-dl](https://github.com/rg3/youtube-dl/)
  * Install via pip: sudo -H pip install --upgrade youtube-dl
* ffmpeg
  * Ubuntu: sudo apt-get install ffmpeg
## Commands
* Simply just send a link to download the video
* \mp4 followed by a link to download a video
* \mp3 followed by a link to download an audio
* \test check if the bot is working
## Running the bot
`python3 bot.py`
