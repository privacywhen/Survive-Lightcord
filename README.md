
# About

[Lightcord](https://lightcord.org) is a simple and customizable client for Discord.
It includes [BandagedBD](https://github.com/rauenzi/BetterDiscordApp), [Glasstron](https://github.com/AryToNeX/Glasstron) and a [discord.js-like api](https://github.com/Lightcord/Lightcord/tree/master/DiscordJS).

# Features

* **Standalone client** - Lightcord is built to be standalone i.e. it will not break on Discord updates!
* **BetterDiscord built in** - Use almost any BetterDiscord plugin or theme!
* **Easy custom rich presence** - Our method of doing this ensures you won't get banned!
* **Made for Privacy** - Lightcord automatically blocks Discord's trackers and blurs your email, keeping your data safe!
* **Free Emotes** - Send any emote to other Lightcord users!
* **Token Login** - (user/bot) [Make **server** calls with bots]
* **AdBlock** - Automatically block bots and ads in your DMs!
* **Always On Top** - Lightcord will always be shown in front of any other windows!
* **Experiments** - Access Discord's hidden experiments with a single click!
* **Tabs** - Have multiple tabs open to do more!
* **HypeSquad Housing** - Easily change your HypeSquad house, no test required!
* **Badges** - Important people like the developers have special badges to make sure you know who is who!

## Planned Features

* **Username History** - Keep track of your past usernames!
* **New Plugin Directory** - Easily install or edit themes and plugins!

# Installing 

## Windows

You can install Lightcord with [scoop](https://github.com/lukesampson/scoop).

```powershell
scoop bucket add extras
scoop install lightcord
```

Alternatively, download the installer from the [releases tab](https://github.com/Lightcord/Lightcord/releases).

## Linux (and ChromeOS)

[This part has moved!](https://github.com/Lightcord/lc-installer-linux)

# Running From Source

Prerequisites: [Node.js](https://nodejs.org/en/) and NPM
To run from source, follow these instructions:

```bash
git clone https://github.com/Lightcord/Lightcord
cd Lightcord
npm run devInstall
npm test
```

*You will have to do that every time you pull/clone*

Lightcord will then launch. If you see the Lightcord icon, you're good to go! 

![icon](https://github.com/Lightcord/Lightcord/blob/master/imagery/68747470733a2f2f692e696d6775722e636f6d2f72486e73504e4f2e706e67.png?raw=true)

Any time you want to launch, just run:

```bash
npm start
```
