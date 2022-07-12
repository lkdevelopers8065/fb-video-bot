# Facebook Video Downloader
![@lkdev_fb_bot](https://user-images.githubusercontent.com/104438811/178399862-f89afa3d-ba16-4bc9-acec-6cc32cd04aa1.png) 

# FB Videos For Telegram (BOT)
With this bot you can make your telegram chat even better, make sure you have your own API_TOKEN! This BOT works **ONLY** with Mentions (at the moment).

## Installing the required modules

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required modules.

```bash
pip install -r requirements.txt
```

## Usage
Make sure to replace <**BOT_TOKEN**> with your own token
```python
bot_token = '<BOT_TOKEN>'
```
Also make sure to change <**@BotName**> with your bot's @
```python
bot.message_handler(func=lambda msg: msg.text is not None and '@BotName' in msg.text)
```
Once you've done those changes, go to your Telegram Chat and add your bot (verify if your bot's privacy is enabled, if so, disable it or give your bot Administrator perms). To use the bot just Mention him and type your video url.

Example:

    @MyBot https://www.facebook.com/frenchguycooking/videos/418182695816256/
The bot should return us the link to our video.


## Tested on

    Python 3.10.5

## License
[GNU 3.0](https://www.gnu.org/licenses/gpl-3.0.html)
