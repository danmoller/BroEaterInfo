# Bro Eater - Discord Moderation Bot

## What is Bro Eater?

Bro Eater is a Dirscord Bot that you can add to your Discord server to control certain forms of spam, particularly Mr B__st spam, that usually carry a text saying "bro".    
When the bot identifies a spam message, the message is automatically deleted and all actions of the bot are logged in a specific channel.   

## How to use

By using Bro Eater, you agree with our terms of service: https://danmoller.github.io/BroEaterInfo/Terms_of_Service.html

- Add Bro Eater to your server and grant it the required permissions.
  - This is enough for the bot to start operating on its own, although it's recommended to create its log channel as described below.
  - Beware of channel overrides: the bot needs to be able to "view channel" and "manage messages" in the channels it's intended to operate. 
- To see the bot logs, create a channel called `bro-eater-logs` and give the bot the following permissions:
  - Send text messages in this channel   
  - Embed Links in this channel.
- To use bot commands, add a BroMod role to the people who will operate it.
- Use the command `!brocommands` to list the bot's available commands.
  - Most commands need the "send messages" permission in the channel to work properly (so the bot can respond to your command)  


