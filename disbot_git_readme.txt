Hello there! 

Follow this instruction manual(README file) so that you'll get your doubts clarified.

At first you need to pip install the discord module to execute the code. Not everyone is aware of this module so it may take a while for you to understand the code.

Along with the discord module, you need to pip install OS & dotenv modules.

Remember, just following up this code won't ensure a working application.

You need to enter into the DISCORD developers portal & you need to create an application there initially. 

Without doing that, you cannot do any of the further steps. 

After creating an APPLICATION, give a name for it & follow up all the basic options provided there.Customize the frontend as you would like to.

Open a notepad or whatever file you want to execute this code. 

Follow up the code. In parallel copy the BOT TOKEN ID which is provided below your APPLICATION details. 

Paste that ID in the variable {TOKEN-ID} provided in the program. 

Note: This TOKEN-ID is very important. If you want to follow up the process & develop the bot for further iterations you need to have this ID stored. So it's better to save this code
somewhere you can easily access.

Import all the modules sepcified in the program.

Later on you need to create a text file & type this : 
 	 DISCORD_TOKEN={your-bot-token}
	 DISCORD_GUILD={your-guild-name}

Here the values enclosed in "{}" are variables. Make sure you have the BOT token which I've mentioned above as well as the guild ID(your server ID) ready. Just copy paste them in place of 
variables.

Now save this file with extension ".env"(an environment file) - It acts as a bridge between the discord API & your source code.

Execute the commands in SHELL along with your TOKEN-ID & GUILD-NAME.

This is how you can create the bot & put it online. I've uploaded the basic source code needed to prepare the bot & install it in one of your GUILDS so that you can TEST it.

The bot stays active as long as you keep your kernel running. If you close it, the bot goes offline.

TO host the bot as long as you want you need to open your kernel or you need to buy servers from providers like HEROKU,VPS from contabo,Digital ocean,Hetzner,Discloud etc. There are many other 
providers who can host your BOT.

Follow all the instructions as mentioned. Have a good day & enjoy the bot))
