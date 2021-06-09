# Python Discord Bot Template

<p align="center">
  <a href="//discord.gg/HzJ3Gfr"><img src="https://img.shields.io/discord/739934735387721768?logo=discord"></a>
  <a href="//github.com/kkrypt0nn/Python-Discord-Bot-Template/releases"><img src="https://img.shields.io/github/v/release/kkrypt0nn/Python-Discord-Bot-Template"></a>
  <a href="//github.com/kkrypt0nn/Python-Discord-Bot-Template/commits/main"><img src="https://img.shields.io/github/last-commit/kkrypt0nn/Python-Discord-Bot-Template"></a>
  <a href="//github.com/kkrypt0nn/Python-Discord-Bot-Template/releases"><img src="https://img.shields.io/github/downloads/kkrypt0nn/Python-Discord-Bot-Template/total"></a>
  <a href="//github.com/kkrypt0nn/Python-Discord-Bot-Template/blob/main/LICENSE.md"><img src="https://img.shields.io/github/license/kkrypt0nn/Python-Discord-Bot-Template"></a>
  <a href="//github.com/kkrypt0nn/Python-Discord-Bot-Template"><img src="https://img.shields.io/github/languages/code-size/kkrypt0nn/Python-Discord-Bot-Template"></a>
  <a href="//github.com/kkrypt0nn/Python-Discord-Bot-Template/issues"><img src="https://img.shields.io/github/issues-raw/kkrypt0nn/Python-Discord-Bot-Template"></a>
</p>

This repository is a template that everyone can use for the start of their discord bot.

When I first started creating my discord bot it took me a while to get everything setup and working with cogs and more.
I would've been happy if there were any template existing. However, there wasn't any existing template. That's why I
decided to create my own template to let <b>you</b> guys create your discord bot easily.

Please note that this template is not supposed to be the best template, but a good template to start learning how
discord.py works and to make your own bot in a simple way.

If you plan to use this template to make your own template or bot, you **have to** give me credits somewhere and keep
the copyright notice on the files.
See [the license file](https://github.com/kkrypt0nn/Python-Discord-Bot-Template/blob/master/LICENSE.md) for more
information.

## Authors

* **[Krypton (@kkrypt0nn)](https://github.com/kkrypt0nn)**

## Support

Before requesting support, you should know that this template requires you to have at least a **basic knowledge** of
Python and the library is made for advanced users. Do not use this template if you don't know the
basics. [Here's](https://pythondiscord.com/pages/resources) a link for resources to learn python.

If you need some help for something, do not hesitate to join my discord server [here](https://discord.gg/HzJ3Gfr).

All the updates of the template are available [here](UPDATES.md).

## Disclaimer

**Nothing** is being saved during runtime in the configuration file, please take a look at the [TODO file](TODO.md) to
know if this has been implemented.

Please do not open issues or pull requests about things that are written in the [TODO file](TODO.md), they are **
already** under work for the version 3.0 of the template.

## How to download it

This repository is now a template, on the top left you can simply click on "**Use this template**" to create a GitHub
repository based on this template.

Alternatively you can do the following:

* Clone/Download the repository
    * To clone it and get the updates you can definitely use the command
      `git clone`
* Create a discord bot [here](https://discord.com/developers/applications)
* Get your bot token
* Invite your bot on servers using the following invite:
  https://discordapp.com/oauth2/authorize?&client_id=YOUR_APPLICATION_ID_HERE&scope=bot&permissions=8 (
  Replace `YOUR_APPLICATION_ID_HERE` with the application ID)

## How to set up

To set up the bot I made it as simple as possible. I now created a [config.yaml](config.yaml) file where you can put the
needed things to edit.

Here is an explanation of what everything is:

| Variable              | What it is                                                            |
| ----------------------| ----------------------------------------------------------------------|
| YOUR_BOT_PREFIX_HERE  | The prefix(es) of your bot                                            |
| YOUR_BOT_TOKEN_HERE   | The token of your bot                                                 |
| APPLICATION_ID        | The application ID of your bot                                        |
| OWNERS                | The user ID of all the bot owners                                     |
| BLACKLIST             | The user ID of all the users who can't use the bot                    |

## How to start

To start the bot you simply need to launch, either your terminal (Linux, Mac & Windows), or your Command Prompt (
Windows)
.

Before running the bot you will need to install all the requirements with this command:

```
pip install -r requirements.txt
```

If you have multiple versions of python installed (2.x and 3.x) then you will need to use the following command:

```
python3 bot.py
```

or eventually

```
python3.8 bot.py
```

<br>

If you have just installed python today, then you just need to use the following command:

```
python bot.py
```

## Issues or Questions

If you have any issues or questions of how to code a specific command, you can:

* Join my discord server [here](https://discord.gg/HzJ3Gfr)
* Post them [here](https://github.com/kkrypt0nn/Python-Discord-Bot-Template/issues)

Me or other people will take their time to answer and help you.

## Versioning

We use [SemVer](http://semver.org) for versioning. For the versions available, see
the [tags on this repository](https://github.com/kkrypt0nn/Python-Discord-Bot-Template/tags).

## Built With

* [Python 3.8](https://www.python.org/)

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE.md](LICENSE.md) file for details
