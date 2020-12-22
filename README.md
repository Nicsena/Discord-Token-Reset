# Discord-Token-Reset
## Publicly posted discord tokens will be put here so it can be instantly reset and notify the owner.
### Look Below for a Mini Tutorial if your bot token got posted here!

# NOTICE
# This has been discontinued indefinitely. It will be continued again if I do this again temporary.

# Contact:
## You can in contact with me at **Nicsena#4021** on Discord.
## If you can't get in contact with me, join my [discord server here](https://nsyt.tk/discord) and contact me or Nicholas#6825 there, he may be wondering why that you are DMing him.

# You may be asking "how does this work"?
### Discord scans git repos to see if they contain a working discord bot token on commit and will instantly reset any token that discord finds by safety jim.

# Note:
### I'm like posting working discord bot tokens here to make sure that discord can reset them instantly by safety jim and make sure that other developers' bots don't get hacked and get used for bad things like destroying a server. Make sure that your bot token is in `.env` so people can't see your bot token because it's in `.env`
### Look below for a mini tutorial! I am gonna make a video about on how to add your bot's token to `.env` soon.

# Mini Tutorial:
### 1) Make a file named .env

### 2) Go into the file named: .env and put TOKEN=<YOUR-DISCORD-BOT-TOKEN>
### 2A) Replace <YOUR-DISCORD-BOT-TOKEN> with your Discord Bot Token

### 3) Go to the main bot js file and put client.login(process.env.TOKEN) or bot.login(process.env.TOKEN)

### 4) Remove the code where it contains your bot's token or replace the code with your bot's token with process.env.TOKEN

### 5) Restart the Project

### 6) There you go. Your bot's token can't be found by other people since it's in .env
