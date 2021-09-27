# 5.2 update

**Improved automatic setup**

Users who use programs that attempt to automatically install modules no longer have to use the ForceSetup.py script. 


**Improved login process**

Bots no longer login at a set speed, instead they each login after the previous bot is successfully logged in. This significantly increases login speed, and reduces the number of closed sessions or timeouts.


**Improved terminal output**

Many minor changes have been made to improve visual appeal in the terminal. (Changed text color, reworded errors, fixed typos, etc.)


**Added check for update**

While booting up, the bot now checks if you are using the latest version, and tells you to update if you are not.


**Added Spam Gif command**

"Spam Gif [JID or Username] w/ [Query]" and "GroupSpam Gif [Query]" will now search for and spam gifs.


**Added Poke Gif command**

"Poke Gif [JID or Username] w/ [query]" and "Gif [Query]" will now search for and send a single gif.


**(Premium) Improved AddAll**

AddAll no longer requires you to refresh beforehand, that is now completed in the login process instead. It no longer crashes when used on large botnets.


**(Premium) Improved AntiPurge**

AntiPurge no longer needs a text file to toggle, and is triggered when normal or status messages in a group are recieved rather than set intervals.


**(Premium) Changed Refresh**

Refresh now just triggers sending friend attribution requests to the other bots. 


**(Premium) Removed access keys**

The terminal will now only ask for your name. 


# Ideas I'm currently looking into for future updates:

**Lag warning**

Have the terminal warn the user when they are spamming more than their machine/host can handle. 


**Timeout warning**

Have the terminal warn the user when a login is taking longer than it should.


**Activity logs**

Log all commands sent to the botnet in a text file, and clear that file every time the script is run.


**Login error logs**

Log all login errors into a text file, and clear that file every time the script is run. 


**Login multithreading**

Increase login speed by attempting each login at once in seperate threads. (Currently Kik closes connections when I try this, idk why, looking into solutions)


**Spam image command**

Spam an image that has already been saved to the bot. 


**(Premium) Save image command**

Save an image to use in the above mentioned image spam.


**(Premium) Lockdown command**

Allow users to set a password for their botnet's PM commands or JID lock them.


**(Premium) Group search command**

Search for groups and display a list with basic information about the results.


**(Premium) Group join command**

Join a group found in the above mentioned group search command.


_Have an idea? Let me know! StethoSpasm@Gmail.com_


