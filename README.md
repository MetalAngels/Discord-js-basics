# Discord-js-basics
This is just a guide on how to make a bot but all you need to do is get the token and start it up!

If you need any help, please feel free do DM me on Discord at "Alex the FemBot#3667"

Before you start, install "Visual Studio Code' and "Node.js"
https://code.visualstudio.com/?wt.mc_id=vscom_downloads
https://nodejs.org/en/
Also, don't forget to install the bot.zip file provided!


Go to https://discord.com/developers/applications and click on "New Application"
![alt text](https://i.imgur.com/7qwv6Ey.png/to/img.png)
Set the name to whatever you want your bot to

![alt text](https://i.imgur.com/OXnMcZ3.png/to/img.png)

// You can also set the profile picture to whatever you want it to be

Once you've created the bot, go to the "Bot" tab
![alt text](https://i.imgur.com/vv81rfG.png/to/img.png)
And Click on "Add Bot"
![alt text](https://i.imgur.com/HXBSjER.png/to/img.png)

It should now look like this
![alt text](https://i.imgur.com/mPsmHwi.png/to/img.png)

Now we need to invite the bot to your server

Go back to "General Information" and copy the client ID
![alt text](https://i.imgur.com/Ih1LXy6.png/to/img.png)

Now head over to https://discordapi.com/permissions.html#0 so you can make an invite easily
Set the perms to whatever you want the bot to have (I usually put Administrator on)

Then go to the Link at the bottom (Which is now your bot's invite link) and invite it to your server
![alt text](https://i.imgur.com/KYtfcdr.png/to/img.png)

As you can see here, the bot is offline. Why? Because you need to set the code for it to go online!

Luckily, I have a basic pre-made bot where all you need to do is input the bot's token!
![alt text](https://i.imgur.com/aKXir4x.png/to/img.png)

Head over to "Visual Studio Code" and click: File > Open Folder and open the "Bot" folder you downloaded at the start
![alt text](https://i.imgur.com/xJm6mEn.png/to/img.png)

Once it opens, click on "index.js" and find "BOT_TOKEN_HERE"
![alt text](https://i.imgur.com/7TnGnW2.png/to/img.png)

Don't have the token? That's fine. Just head back over to the Discord Developer Portal and go to the "Bot" tab

Then where it says "Token", copy it and go back to Visual Studio Code
![alt text](https://i.imgur.com/kemvRL0.png/to/img.png)


Go back to where it says "BOT_TOKEN_HERE" and replace it with the token you copied.

Now open the terminal (You can click on the top "Terminal > New Terminal" or use the shortcut "ctrl+shift+(Tilde key)")

Once it's open, type "node ." and the bot should now go online!
![alt text](https://i.imgur.com/covbreT.png/to/img.png)


Online as shown here!
![alt text](https://i.imgur.com/xxaguFx.png.png/to/img.png)


And that's it!

If you want a different prefix, go to "const prefix = '!';" and change the ! to whatever you want (make sure it's actually a prefix)

Again, if you need help, DM me on Discord at "Alex the FemBot#3667"
