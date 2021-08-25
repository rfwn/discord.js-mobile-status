1 - node_modules > discord.js > esm > src > util > Constants.js

2 - ctrl+F and search for "$browser", then you will se "$browser: 'discord.js'"

3 - change "$browser: 'discord.js'" to "$browser: 'Discord Android'" and it's done, now you should have the mobile status on your bot

4 - Or just put this on your main file "Discord.Constants.DefaultOptions.ws.properties.$browser = "Discord Android";"
