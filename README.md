# How To Host
The easiest way to deploy this Bot
<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/QueenArzoo/CallMusic"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-black?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

Get STRING_NAME from here:

[![GenerateString](https://img.shields.io/badge/repl.it-generateString-yellowgreen)](https://replit.com/@QueenArzoo/VCPlayBot)

### Mandatory Vars.

- Some Of The Mandatory Vars Are :-
   - `API_ID` :  Give API_ID of your Alternate Telegram Account. also get from here [@APIInfoBot](https://t.me/APIinfoBot)
   - `API_HASH` :  Give API_HASH of your Alternate Telegram Account. also get from here [@APIInfoBot](https://t.me/APIinfoBot)
   - `STRING_NAME` :  Make a string session from [here](https://replit.com/@QueenArzoo/VCPlayBot)
   - `BOT_TOKEN` :  Make a Bot from [@Botfather](https://t.me/botfather) and fill it's bot token.
   - `SUDO_USERS` :  Fill Userid of yhe users whom you want to be able to control the bot. You can add multiple id by giving a space in b/w each id.







## Commands

| Command | Description                                          |
| ------- | ---------------------------------------------------- |
| /play   | play the replied audio file or YouTube video         |
| /pause  | pause the audio stream                               |
| /resume | resume the audio stream                              |
| /skip   | skip the current audio stream                        |
| /mute   | mute the userbot                                     |
| /unmute | unmute the userbot                                   |
| /stop   | clear the queue and remove the userbot from the call |


## Requirements

- FFmpeg
- Python 3.7+

## Deployment

### Config

Copy `example.env` to `.env` and fill it with your credentials.

### The good way

1. Install Python requirements:
   ```bash
   pip install -U -r requirements.txt
   ```
2. Run:
   ```bash
   python main.py
   ```

### Docker

1. Build:
   ```bash
   docker build -t musicplayer .
   ```
2. Run:
   ```bash
   docker run --env-file .env musicplayer
   ```

## License

### GNU Affero General Public License v3.0

[Read more](http://www.gnu.org/licenses/#AGPL)
