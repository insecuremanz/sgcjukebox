<h1 align="centre">SGC Music Projects </h1>

### A bot that can play music on Telegram Group and Channel Voice Chats
### Available on telegram as [@sobatgabutz](https://t.me/sobatgabutz)

<p align="center">
  <img src="https://telegra.ph/file/68af50ef043dd26466c84.jpg">
</p>
<h2> Features </h2>

- Thumbnail Support
- Playlist Support
- Current playback support
- Showing track names when skipping
- Zero downtime, Fully Stable
- Deezer,Youtube & Saavn playback support
- Settings panel
- Control with buttons
- Userbot auto join

## Deployment

### ⚔ Self-hosting (For Devs) 
```sh
# Install Git First (apt-instll git)
$ git clone https://github.com/insecuremanz/sgcjukebox
$ cd sgc-MusicProject
# Upgrade sources
# Install All Requirements 
$ pip(3) install -r requirements.txt
# Rename example.env to local.env and fill
$ npm i -g npm
# Start Bot 
$ python(3) -m sgcProject
```

### DEPLOYY HEROKU

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/insecuremanz/sgcjukebox)

Get pyrogram (p)  `SESSION` from here:
[![Run on Repl.it](https://repl.it/badge/github/vckyou/PyrogramString)](https://repl.it/@vckyou/PyrogramString?lite=1&outputonly=1)

### Commands for Group 🛠
#### For all in group

- `/playlist` - Show now playing list
- `/current` - Show now playing
- `/song <song name>` - download songs you want quickly
- `/search <query>` - search videos on youtube with details
- `/deezer <song name>` - download songs you want quickly via deezer
- `/saavn <song name>` - download songs you want quickly via saavn
- `/video <song name>` - download videos you want quickly

#### Admins only.
- `/play <song name>` - play song you requested
- `/play <reply to audio>` - play replied file
- `/dplay <song name>` - play song you requested via deezer
- `/splay <song name>` - play song you requested via jio saavn
- `/player` - open music player settings panel
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play
- `/userbotjoin` - invite assistant to your chat
- `/userbotleave` - remove assistant from your chat
- `/admincache` - Refresh admin list


#### Pmpermit
- `.yes` - approove someone to pm you
- `.no` - disapproove someone to pm you
+ Sudo Users can execute any command in any groups

