# DiscordBotWokHandler

Uses discord.js library combined with WOKCommands to create a basic demobot.o create a basic demobot.

https://discord.js.org/#/

https://docs.wornoffkeys.com/

## Getting Started

Start here: https://discord.com/developers/applications

Click "New Application" - name the Application.

Click "Bot" - "Add Bot"

Go to Oauth2. URL Generator. Click "Bot" and "Administrator" (stick with Administrator for demo purposes)

Copy autogenerated link at bottom of page. Visit the link. Connect the bot to a test server of your choice and close window. Youve connected the bot to your server!

Now, go back to "Bot" and click "Reset Token" to get your token.

Create .env file and add the TOKEN to the file.

You can also add your mongodb DATABASE_URI in the .env file if you'd like (see line 33 of index.ts for database usage through WOKCommand Handler)

Next install dependencies

### Dependencies

npm install

### Executing program

-   Run "npm run dev". This will set up your nodemon server for your bot to run. This should connect your code to the bot.

Slash commands working:
/add does a quick add inline demo
/addrole allows making of a role based on the message of the user (not sure i understand this use case?)
/buttons this will show various button demos
/send will send a specific message to a specific channel

Legacy commands working:
!collector shows a basic reaction collector/counter
!ping basic "pong" response

```

https://docs.wornoffkeys.com/

https://www.youtube.com/watch?v=JMmUW4d3Noc&list=PLaxxQQak6D_f4Z5DtQo0b1McgjLVHmE8Q

Has the command handler WOKCommands used throughout. Lots of video tutorials and documentation which was quite helpful. He also has a discord with active helpers there too!
```
