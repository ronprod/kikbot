IMPORTANT: As of 09/17/2020 (1pm MST) there is an issue with bot logins. Rumor has it that this is an action taken by Kik, as there have been no changes made to this code to cause this. Other scripts made with Tomer8007 are having the same issue. Please be patient while I look into this!
- Stetho

# About
This is a Kik botnet that uses the [Tomer8007 Kik Bot API](https://github.com/tomer8007/kik-bot-api-unofficial) to spam users and groups.
(Version 5.1)

I've hosted a copy on Replit for those of you who want to run it from your web browser, which you can find [here](https://replit.com/@StethoSaysHello/KikBotnet?v=1).

# Installation

Make sure you are using Python 3.6+, not python 2.7!

Use `git clone https://github.com/StethoSaysHello/KikBotnet`

Then just run [botnet.py](https://github.com/StethoSaysHello/KikBotnet/blob/main/botnet.py), it will install all of the needed dependancies for you. 

_Alternatively, you can just copy and paste the contents of [botnet.py](https://github.com/StethoSaysHello/KikBotnet/blob/main/botnet.py)._

If you are running this on a program that attempts to automatically install packages from import statements, automatic setup will not work.
If this happens, use [forcesetup.py](https://github.com/StethoSaysHello/KikBotnet/blob/main/forcesetup.py) instead of [botnet.py](https://github.com/StethoSaysHello/KikBotnet/blob/main/botnet.py). 
(You can tell when this happens because it will give you an AttributeError, the kik-bot-api-unofficial folder will not appear, and it will tell you that you have captchas when you do not.)

# Usage

Once you run the script, the prompts should be self explanatory, but if you need an elaboration on each step [click here](https://pastebin.com/6kdHjVKk).

You cannot trigger the botnet from the terminal, you need to trigger the bots themselves via messages on Kik. To trigger an entire botnet, either add the whole botnet to a group and use the command, or send a mass message to each bot's PMs via modded Kik. Keep in mind that you need to make your own bot accounts, it will not make them for you!

- **"Spam [JID or Username] w/ [Message]"** -  Used to spam a user's PMs.

- **"Poke [JID or username] w/ [Message]"** -  Used for forwarding a single message to a user.

- **"Friend"** - Used to add the bot as a friend so that you can add it to groups.

- **"SendFriend [JID or Username]"** - Used to send a friend attribution request to a user.

- **"GroupSpam [Message]"** - Used to spam the group that this command is used in.

- **"Leave [GJID]"** - Used for making your bot(s) leave groups.

# Disclaimers

None of the code here is taken from other developers! It does not contain any malicious or hidden content, you are more than welcome to share and edit this code. 

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

(Don't like the paywall? [_Make it yourself._](https://pastebin.com/nZJsCRGX))
