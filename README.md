# RhinoBot: The music bot for Discord.

MusicBot is a Discord music bot written in [Python](https://www.python.org "Python homepage"). It plays requested songs and if the queue becomes empty it will play through a list of existing songs.

### How do I set it up?

- [Windows Tutorial](https://github.com/SexualRhinoceros/MusicBot/wiki/Installation-guide-for-Windows-7-and-up "Windows instructions")
- [Linux Tutorial](https://github.com/SexualRhinoceros/MusicBot/wiki/Installation-guide-for-Ubuntu-14.04-and-other-versions "Linux instructions")
- [Docker Tutorial](https://github.com/SexualRhinoceros/MusicBot/wiki/Installation-guide-for-Docker)
- [OSX Tutorial](https://github.com/SexualRhinoceros/MusicBot/wiki/Installation-guide-for-OSX)

### Commands

Commands are listed [here](https://github.com/SexualRhinoceros/MusicBot/wiki/Commands-list "Commands list").

### Configuration

The main configuration file is `config/options.ini`, but is not included.  Simply make a copy of `example_options.ini` and rename to `options.ini`.  See `example_options.ini` for more information on how to configure it.

### Great, now how do I use it?
Download the bot, set the dependencies up, then run `runbot.bat`! (or `run.sh` on mac/linux)  Read the tutorial if you don't know what to do.

If you have any errors, read the FAQ. If that didn't help, you can ask for assistance on the discord help server. Is is recommended to take screenshots so the developers can see errors.

[Rhino Help Server](http://discord.me/rhinohelp "Discord link")

### FAQ

Some frequently asked questions are listed on the wiki [here](https://github.com/SexualRhinoceros/MusicBot/wiki/FAQ "Wiki").

# Our changes

> Bot use also Discord OAuth2

> To login with **token** you need only token, bot also will have additional stability if login through token (create it here: [Discord Applications](https://discordapp.com/developers/applications/me "Discord Applications"))

> New commands: h (help), p / music / m / add (play), nq (play, but add on second position), d (skip), s (search), remove / rem, undo, q (queue), nq (queue, but only current song), next (queue, but only next), c (clear), v (volume), setavatar, setnick, setname, unskip, fixlinkinautoplaylist.

> New functional: bot can play at multiple servers (no need multiple accounts or program instances), every song now will adding in autoplaylist and will playing if queue is empty, if you no need this, you may remove it or undo (undo remove command), np show url to song, unskipping system; clearing now can clear only specifyed user messages, instead all; songs always keep in chat, so you no lose it; you will able to change bot name, nick avatar and also grant it to some people if you want, fixlinkinautoplaylist command stylize playlist inlo one style, clear tags like &t=, etc.
