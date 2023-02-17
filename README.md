# Discord.js v14 slashCommand Handler
THE BEST DJS V14 COMMAND HANDLER.
Credits: leaf
Discord: https://discord.gg/6cgRbJzX8Y
### I only uploaded this cmd handler to github.
Otherwise the owner had uploaded it in his discord

# Features
### 1. Easy to use (Use it with the easiest way to create an SlashCommand)
### 2. Mongoose Support
### 3. Users without permission won't see command in the slash command list.

# Setup
## Setting up Bot
### Go to config.js and write your details
```js
require("dotenv").config(); // remove this line if you are using replit

module.exports = {
    token: process.env.TOKEN || "", // your bot token
    mongourl: process.env.MONGO_URI || "", // mongoose connection string
    clientID: process.env.CLIENT_ID || "", // your bot client id
};
```

## Status
### if you want to change your bot's status Go to structure/client.js and you will see this line
```js
presence: {
                status: "online",
                activities: [
                    {
                        name: "Version " + require("../package.json").version,
                        type: ActivityType.Watching,
                    },
                ],
            },
```


# ENJOY
