<div align="center">
<img src="https://i.ytimg.com/vi/nkhVzxXnuSQ/maxresdefault.jpg" alt="HisokaBot" width="500" />

# _**HisokaBot**_

> HisokaBot is a multipurpose WhatsApp bot using wa-automate-nodejs library!
> Script Copy From [BocchiBot](https://github.com/SlavyanDesu/BocchiBot)
>
>

# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://www.gyan.dev/ffmpeg/builds/)
* [libwebp](https://developers.google.com/speed/webp/download)
* Any text editor

# Installation
## 📝 Cloning this repo
```cmd
> git clone https://github.com/dxxoo/HisokaBOT-Whatsapp-Bot.git
> cd HisokaBOT-Whatsapp-Bot
```

## ✍️ Editing the file
Edit the required value in `config.json`.
```json
{
    "ownerBot": "625839154607@c.us", 
    "prefix": "$",
    "uaOverride": "WhatsApp/2.2037.6 Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/85.0.4183.83 Safari/537.36",
    "itech": "api-key",
    "nao": "api-key",
    "vhtear": "api-key",
    "melodic": "administrator",
    "tobz": "BotWeA"
}
```

`ownerBot`: your WhatsApp number.  
`prefix`: bot's prefix.  
`uaOverride`: your user agent.  
`itech`: I-Tech API key. You can get it [here](https://api.i-tech.id) by creating an account. After that, set your server/host static IP in [here](https://api.i-tech.id/settings/profile).  
`nao`: SauceNAO API key. You can get it [here](https://saucenao.com/user.php) by creating an account.  
`vhtear`: VHTear API key. You can get it [here](https://api.vhtear.com/) by purchasing his API key.  
`melodic`: MelodicXT API key. You can use `administrator` key.   
`tobz`: Tobz API key. You can use `BotWeA` key.   

## 🗣️ Changing language
If you want to change the language to English, replace all `ind` function to `eng`.   
Example:
```js
ind.wrongFormat()
```
To:
```js
eng.wrongFormat()
```

## 🛠️ Installing the FFmpeg
* Download one of the available versions of FFmpeg by clicking [this link](https://www.gyan.dev/ffmpeg/builds/).
* Extract the file to `C:\` path.
* Rename the extracted folder to `ffmpeg`.
* Run Command Prompt as Administrator.
* Run this command:
```cmd
> setx /m PATH "C:\ffmpeg\bin;%PATH%"
```
It will give us a callback like `SUCCESS: specified value was saved`.
* Now that you've FFmpeg installed, verify that it's working by running this command to see version number:
```cmd
> ffmpeg -version
```

## 📷 Installing the libwebp
The installation is same as you install FFmpeg but whatever. I will make it clear.
* Download the file according to the OS you are using by clicking [this link](https://developers.google.com/speed/webp/download).
* Extract the file to `C:\` path.
* Rename the extracted file to `libwebp`.
* Run Command Prompt as Administrator.
* Run this command:
```cmd
> setx /m PATH "C:\libwebp\bin;%PATH%"
```
It will give us a callback like `SUCCESS: specified value was saved`.
* Now that you've libwebp installed, verify that it's installed by running this command to see version number:
```cmd
> webpmux -version
```

## 🔍 Installing the dependencies
```cmd
> npm install
```

## 🆗 Running the bot
Regular node:
```cmd
> npm start
```

PM2:
```cmd
> pm2 start index.js
> pm2 monit
```

PM2 with cron job (restart after 5 hours):
```cmd
> pm2 start index.js --cron "* */5 * * *"
> pm2 monit
```

After that scan the QR code using your WhatsApp in your phone!

# Features
If you want to unlock premium commands, please buy me a coffee at least 1 on Ko-fi platform.

|     Leveling     |  Availability  |
| :--------------: | :------------: |
| Leveling         |       ✔️       |
| Set level color  |      Soon      |
| Set bar color    |      Soon      |

|     Sticker Maker     | Availability |
| :-------------------: | :----------: |
| Send/reply image      |      ✔️      |
| Send/reply GIF        |      ✔️      |
| Send/reply MP4        |      ✔️      |
| Text to sticker       |      ✔️      |
| Text to sticker GIF   |      ✔️      |
| Sticker to image      |      ✔️      |
| Sticker WM            |      ✔️      |
| Take sticker          |      ✔️      |

|      Downloader     | Availability |
| :-----------------: | :----------: |
| Facebook video      |      ✔️      |
| YouTube audio/video |      ✔️      |
| Joox musics         |      ✔️      |
| TikTok video        |      ✔️      |
| TikTok profile pic  |      ✔️      |
| Twitter video/image |      ✔️      |
| Instagram post      |      ✔️      |
| Instagram story     |      ✔️      |
| LK21                |      ✔️      |
| TikTok no WM        |      ✔️      |

|         Misc         | Availability |
| :------------------: | :----------: |
| Say                  |      ✔️      |
| Search lyrics        |      ✔️      |
| Shortlink maker      |      ✔️      |
| Wikipedia (EN)       |      ✔️      |
| Wikipedia (ID)       |      ✔️      |
| KBBI scarper         |      ✔️      |
| Stalk IG account     |      ✔️      |
| GSMArena scraper     |      ✔️      |
| Search food receipts |      ✔️      |
| YouTube search       |      ✔️      |
| Text to speech       |      ✔️      |
| AFK                  |      ✔️      |
| Distance calculator  |      ✔️      |
| Sticker search       |      ✔️      |
| Calculator           |      ✔️      |
| Al-Qur'an surah      |      ✔️      |
| List surah           |      ✔️      |
| Random contact       |      ✔️      |
| YouTube play         |      ✔️      |
| Whois                |      ✔️      |
| SMS gateway          |      ✔️      |
| Al-Qur'an tafseer    |      ✔️      |
| Al-Kitab search      |      ✔️      |
| LK21 scraper         |      ✔️      |
| Reminder             |      ✔️      |
| Image uploader       |      ✔️      |
| Sholat schedule      |      ✔️      |
| Latest Line stickers |      ✔️      |
| Check postage        |      ✔️      |
| Sending email        |      ✔️      |
| Random quotes        |      ✔️      |
| Genshin chara info   |      ✔️      |

|          Fun          | Availability |
| :-------------------: | :----------: |
| Weton jodoh           |      ✔️      |
| Horoscope             |      ✔️      |
| Harta tahta maker     |      ✔️      |
| Writing text maker    |      ✔️      |
| Glitch text maker     |      ✔️      |
| SimSimi chatbot       |      ✔️      |
| Blackpink logo maker  |      ✔️      |
| Pornhub logo maker    |      ✔️      |
| Galaxy text maker     |      ✔️      |
| Truth or dare         |      ✔️      |
| Asupan TikTok         |      ✔️      |
| PH comment maker      |      ✔️      |
| Triggered maker       |      ✔️      |
| Kiss image maker      |      ✔️      |
| 3D text maker         |      ✔️      |
| Freefire logo maker   |      ✔️      |
| Freefire banner maker |      ✔️      |
| Sliding text maker    |      ✔️      |
| Hero ML maker         |      ✔️      |
| Fire text maker       |      ✔️      |
| Couple balloon maker  |      ✔️      |
| Wasted maker          |      ✔️      |
| Cakl Lontong quiz     |      ✔️      |
| Hilih-ify text        |      ✔️      |
| Tebak gambar quiz     |      ✔️      |
| Random doge stickers  |      ✔️      |
| Dice                  |      ✔️      |

|       Weeb Zone       | Availability |
| :-------------------: | :----------: |
| Random neko girl      |      ✔️      |
| Random wallpaper      |      ✔️      |
| Random kemonomimi     |      ✔️      |
| Kusonime scraper      |      ✔️      |
| Komiku scraper        |      ✔️      |
| Anime tracer          |      ✔️      |
| Source finder         |      ✔️      |
| Random waifu pics     |      ✔️      |
| Anitoki latest update |      ✔️      |
| Random anime stickers |      ✔️      |
| Neonime latest update |      ✔️      |
| Anoboy on-going list  |      ✔️      |

|        Bot       | Availability |
| :--------------: | :----------: |
| Server usage     |      ✔️      |
| Blocked list     |      ✔️      |
| Ping             |      ✔️      |
| Delete messages  |      ✔️      |
| Bug report       |      ✔️      |
| Join group       |      ✔️      |
| Check serials    |      ✔️      |

|        Owner       | Availability |
| :----------------: | :----------: |
| Broadcasting       |      ✔️      |
| Clear all messages |      ✔️      |
| Leave all groups   |      ✔️      |
| Get snapshot       |      ✔️      |
| Ban                |      ✔️      |
| Eval               |      ✔️      |
| Shutdown           |      ✔️      |
| Add premium user   |      ✔️      |
| Set bot's info     |      ✔️      |
| Mute bot           |      ✔️      |

|    Moderation    | Availability |
| :--------------: | :----------: |
| Add              |      ✔️      |
| Kick             |      ✔️      |
| Promote          |      ✔️      |
| Demote           |      ✔️      |
| Leave bot        |      ✔️      |
| Everyone         |      ✔️      |
| Toogle NSFW      |      ✔️      |
| Set group icon   |      ✔️      |
| Anti-group link  |      ✔️      |
| Toogle welcome   |      ✔️      |
| Auto-sticker     |      ✔️      |
| Mute group       |      ✔️      |
| Anti-NSFW link   |      ✔️      |
| Anti-porn        |    Premium   |

|        NSFW        | Availability |
| :----------------: | :----------: |
| Lewds              |      ✔️      |
| nHentai lookup     |      ✔️      |
| Fetish             |      ✔️      |
| Latest Nekopoi     |      ✔️      |
| Pornhub downloader |      ✔️      |
| Waifu 18+          |      ✔️      |
| Yuri               |      ✔️      |
| Femdom             |      ✔️      |
| Lewd avatars       |      ✔️      |
| nHentai search     |      ✔️      |
| nHentai downloader |    Premium   |
| Multi-lewds        |    Premium   |
| Multi-fetish       |    Premium   |

# Thanks to
* [`open-wa/wa-automate-nodejs`](https://github.com/open-wa/wa-automate-nodejs)
* [`YogaSakti/imageToSticker`](https://github.com/YogaSakti/imageToSticker)
* [`SlavyanDesu`](https://github.com/SlavyanDesu)
