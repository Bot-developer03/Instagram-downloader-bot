<h1 align="center">Telegram Bot</h1>
<p align="center">A telegram bot to download media from Instagram! No API Key or Login Needed!<p>

## Requirements
* You must have python installed (of course)
* You must install the following modules

 python-telegram-bot
 requests
## Installation
```python
git clone https://bot-developer03/Instagram-downloader-bot
```
```python
cd Instagram-downloader-bot
```
```python
pip3 install -r requirements.txt
```
## How to use
1. Make sure you installed all the requirements
2. Open Telegram, go to [@BotFather](https://t.me/botfather) and create a new Bot.
3. Copy the Bot Access Token.
4. Open the main.py file using any text editor, go down to line 116 and paste your token there.
5. Save the file and run the script!by typing

```python
python main.py
```

## How it works
This bot uses the Instagram public GraphQL API. When a link is sent to the bot, a request to the API is sent and a json response is received. The bot will get every media included in the given post and send it to the user.

## NOTE
Please note that the API requests will not work (aka the bot wouldn't be able to send the media) if you are hosting the bot on a platform like Heroku or PythonAnyWhere. If you are planning to keep the bot running 24/7 you must keep it running on your local machine forever or on a Raspberry Pi. Or just find an alternative API (most of them are paid ones)