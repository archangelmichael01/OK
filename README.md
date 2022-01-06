# MULTI VC USERBOTS
Fully working VC (user)Bot, based on py-tgcalls and py-tgcalls-wrapper with minimal [features](#Features).   

## Commands:   
- [x] `!on` - Check if the (user)bot is online.   
- [x] `!help` - Help message.   
- [x] `!stream` - Either give a youtube URL or reply to a telegram file to play it.   
- [x] `!pause` - Pause the stream.   
- [x] `!resume` - Yes, resume.   

## Deploying
* To heroku:   
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](http://heroku.com/deploy?template=https://github.com/MrRizoel/MultiVCuserbots)   

* Local machine/VPS:   
`git clone https://github.com/MrRizoel/MultiVCuserbots`   
`pip install -r requirements.txt`   
`apt-get install ffmpeg`   
`touch .env && nano .env`, fill in the vars as in [.env.sample](./.env.sample)   
`python bot.py`   

## SESSION
Either run [sessiongen.py](./sessiongen.py) locally or run it on [repl.it by clicking here.](https://replit.com/@RiZoeL/PYROSESSION#main.py)

## Support
- [@DNHxHELL](https://t.me/RiZoeLX)   


## Features
  
- A queue system.   
- Play with song name.   
- Auto-leave VC on song end.   
- JoinVC/LeaveVC.   
- Updater.   


## Credits
- [pytgcalls](https://github.com/pytgcalls/pytgcalls)  
- [Pyrogram](https://github.com/pyrogram/pyrogram)   
- [VCBOT](https://github.com/xditya/VCBot)
