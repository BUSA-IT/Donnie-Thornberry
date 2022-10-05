# **Donnie Thornberry Troll Bot**

Created this bot to troll my friends in discord. Bot joins the channel and Donnie Thornberry speaks over the designated target when they try to speak. I'll probably fiddle with this and clean it up over the next few days.

**Important note:** This bot was in no way intended to be mass used. Also this code is sloppy in it's current state and if you use this enough I'm sure it is littered with bugs in edge cases that I did not bother testing because again, I can not stress enough, that this was a project that I did in a hurry as a joke for tik tok. I also added all the message command code after the fact to make it slightly more user friendly, it was all just hardcoded with user id's for my friends prior to adding this code.

Feel free to fork the bot and extend it in anyway you can think of also I'm open to PR's if you are interested in that.
# Usage Instructions

### **Prerequisites**

- [Node.JS](https://nodejs.org/en/) 14.0.0 or higher.
- You will need basic knowledge of node.js and how to navigate via cmd prompt or terminal.
- Setup a discord bot account and get your bot token. Instructions on this can be found [here](https://discordjs.guide/preparations/setting-up-a-bot-application.html#keeping-your-token-safe).

### **Instructions**
- **Step 1:** `git-clone` or download the project from this repo to your machine. CD into the project dir and run `npm install` to install dependencies.
- **Step 2**: In the project directory create a file named `.env` and copy the contents of `.env.example` into the new file. Replace the placeholder TOKEN with your own.
- **Step 3**: Start the bot by navigating in CMD prompt or terminal into the project dir and running `node bot.js` or using a process manager like [PM2](https://www.npmjs.com/package/pm2) OR [forever](https://www.npmjs.com/package/forever)
- **Step 4:** The default command prefix for the bot is `don!` Running `don!help` will give you all the commands necassary. Essentially the main command is `don!target @(your target here)`. Also there is `don!start` and `don!stop`. By default he is turned on so to begin trolling your friends you should just have to target them.
