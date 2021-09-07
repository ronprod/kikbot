# About
This is a Kik botnet that uses the [Tomer8007 Kik Bot API](https://github.com/tomer8007/kik-bot-api-unofficial) to spam users and groups.
(Version 5.1)

I've hosted a copy on Replit for those of you who want to run it from your web browser, which you can find [here](https://replit.com/@StethoSaysHello/KikBotnet?v=1).

# Installation

Make sure you are using Python 3.6+, not python 2.7!

Use `git clone https://github.com/StethoSaysHello/KikBotnet`

Then just run [main.py](https://github.com/StethoSaysHello/KikBotnet/blob/main/main.py), it will install all of the needed dependancies for you. 

_Alternatively, you can just copy and paste the contents of [main.py](https://github.com/StethoSaysHello/KikBotnet/blob/main/main.py)._

If you are running this on a program that attempts to automatically install packages from import statements, automatic setup will not work.
If this happens, install dependancies manually using the following commands:

`git clone -b new https://github.com/StethoSaysHello/kik-bot-api-unofficial`

`pip3 install ./kik-bot-api-unofficial`

Then the program should automatically install emoji, colorama, and kik_unofficial when you run [main.py](https://github.com/StethoSaysHello/KikBotnet/blob/main/main.py).

# Usage

Once you run [main.py](https://github.com/StethoSaysHello/KikBotnet/blob/main/main.py), the prompts should be self explanatory, but if you need an elaboration on each step [click here](https://pastebin.com/6kdHjVKk).

You cannot trigger the botnet from the terminal, you need to trigger the bots themselves via messages on Kik. To trigger an entire botnet, either add the whole botnet to a group and use the command, or send a mass message to each bot's PMs via modded Kik.

- **"Spam [JID or Username] w/ [Message]"** -  Used to spam a user's PMs.

- **"Poke [JID or username] w/ [Message]"** -  Used for forwarding a single message to a user.

- **"Friend"** - Used to add the bot as a friend so that you can add it to groups.

- **"SendFriend [JID or Username]"** - Used to send a friend attribution request to a user.

- **"GroupSpam [Message]"** - Used to spam the group that this command is used in.

- **"Leave [GJID]"** - Used for making your bot(s) leave groups.

# Disclaimers

None of the code here is "skidded" (stolen from other developers). It contains no malicious or hidden content, you are more than welcome to share and edit this code. 

Previous versions of this bot were obfuscated and required an access key, these limits no longer apply. 

# Premium

Paid users get access to a premium version of this botnet!
It contains the following additional commands:

- **"Refresh"** - Used to grab all bots JIDs and friend each of them.

- **"Antipurge [on/off]"** - Used to toggle repeatedly unbanning/adding/promoting all other bots.

- **"Antipurge check"** - Used to check if antipurge is on.

- **"AddAll"** - Used for adding all other bots to a group.

- **"Promote [JID/Username]"** - Used for promoting users when bot has admin.

- **"Demote [JID/Username]"** - Used for demoting users when bot has admin.

These features are **NOT** in this version. To gain access to the premium version, email stethospasm@gmail.com

(If you don't like the paywall, _make it yourself._)
