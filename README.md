![11111 bersrerk](https://github.com/user-attachments/assets/b077fb2b-9e74-433d-b5a9-69ff2deb0370)

# Deploy to HEROKU

**<u>Important Note:</u>**
1. Add all of your private files here: `config.env`, `token.pickle`, `rcl.conf`, `accounts.zip`, `shorteners.txt` etc...

**<u>Mandatory Veriables in Config:</u>**

- `UPSTREAM_REPO`: Your github repository link, if your repo is private add `https://<deploy_token>:<empty_password>@gitlab.com/<your_username>/<repository_name>
` format. `Str`.
  - **NOTE**: Don't forget to remove '<' and '>' . Follow [**THIS TUTORIAL**](https://graph.org/GitLab-Upstream-Tutorial-06-02) to generate upstream repo. 
              - Any change in docker or requirements you need to deploy/build again with updated repo to take effect. 
              - **DON'T delete .gitignore file**. For more information read.
- `UPSTREAM_BRANCH`: Upstream branch for update. Default is `upstream`. `Str`

- `BOT_TOKEN`: The Telegram Bot Token that you got from [**BotFather**](https://t.me/BotFather). `Str`
- `OWNER_ID`: The Telegram User ID (not username) of the Owner of the bot. `Int`
- `TELEGRAM_API`: This is to authenticate your Telegram account for downloading Telegram files. You can get this from **<https://my.telegram.org>**. `Int`
- `TELEGRAM_HASH`: This is to authenticate your Telegram account for downloading Telegram files. You can get this from **<https://my.telegram.org>**. `Str`

- `BASE_URL`: Add a valid `BASE URL` to use torrent selection. Copy it from your heroku app. Right click on `OPEN APP` and copy link address. Format of URL should be `https://APPNAME-IDENTIFIER.herokuapp.com/`, where `APPNAME` is the name of your heroku app and IDENTIFIER is an unic number. Example: `https://ZeeApp1-mjw69x6ex696.herokuapp.com/`. `Str`
- `TORRENT_TIMEOUT`: Timeout of dead torrents downloading with qBittorrent and Aria2c in seconds. `Int`

---
### For farther assistance visit my support group: [**@Asa Mirror**](https://t.me/ASA_MIKATA1).
---

## Deploy using CLI

- Carefully copy-paste every CMD one by one. If you miss maybe your BOT will not run.

## Deploy using Google Colab

- Visit this [**LINK**](https://shorturl.at/pCLN5) and follow on-screen instructions.

---
### Demo BOT available here: [**@Beserk Mirror**](https://t.me/ZeninToji_bot).
---
