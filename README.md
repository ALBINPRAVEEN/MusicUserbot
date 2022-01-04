<h1 align= center><b>⭐️ Music Player Userbot⭐️</b></h1>
<h3 align = center> A Telegram Music Bot written in Python using Pyrogram and Py-Tgcalls </h3>


## 🚀 <a name="deploy"></a>Deploy

[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

Note: `First Fork The Repo Then Click On Deploy To Heroku Button!`


## ☁️ <a name="self_host"></a>Self Host

```bash
$ git clone https://github.com/ALBINPRAVEEN/MusicUserbot
$ cd MusicUserbot
$ cp sample.env .env
< edit .env with your own values >
$ sudo docker build . -t musicplayer
$ sudo docker run musicplayer
```

## ⚒ <a name="configs"></a>Configs

- `API_ID`: Telegram app id.
- `API_HASH`: Telegram app hash.
- `SESSION`: Pyrogram string session. You can generate from [here](https://replit.com/@ALBINPRAVEEN1/getStringName).
- `SUDOERS`: ID of sudo users (separate multiple ids with space).
- `QUALITY`: Custom stream quality for the userbot in vc. Default: `high`
- `PREFIX`: Commad prefixes (separate multiple prefix with space). Eg: `! /`
- `LANGUAGE`: An [available](#languages) bot language (can change it anytime). Default: `en`

## 📄 <a name="commands"></a>Commands

Command | Description
:--- | :---
• !ping | Check if alive or not
• !start / !help | Show the help for commands
• !mode / !switch | Switch the stream mode (audio/video)
• !p / !play [song name or youtube link] | Play a song in vc, if already playing add to queue
• !radio / !stream [radio url or stream link] | Play a live stream in vc, if already playing add to queue
• !pl / !playlist [youtube playlist link] | Play the whole youtube playlist at once
• !skip / !next | Skip to the next song
• !m / !mute | Mute the current stream
• !um / !unmute | Unmute the muted stream
• !ps / !pause | Pause the current stream
• !rs / !resume | Resume the paused stream
• !list / !queue | Show the songs in the queue
• !mix / !shuffle | Shuflle the queued playlist
• !loop / !repeat | Enable or disable the loop mode
• !lang / language [language code] | Set the bot language in group
• !ip / !import | Import queue from exported file
• !ep / !export | Export the queue for import in future
• !stop / !leave | Leave from vc and clear the queue

## 🗣 <a name="languages"></a>Languages

```text
en    English
```
## 🛫 <a name="supports"></a>Supports

For any kind of help join [our support group](https://t.me/musicwithalby).
