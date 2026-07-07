# Bro Eater - Discord Moderation Bot

## What is Bro Eater?

Bro Eater is a Dirscord Bot that you can add to your Discord server to control certain forms of spam, particularly Mr B__st spam, that usually carry a text saying "bro".    
When the bot identifies a spam message, the message is automatically deleted and all actions of the bot are logged in a specific channel.   

## How to use

- Add Bro Eater to your server and grant it the required permissions.
  - This is enough for the bot to start operating on its own, although it's recommended to create its log channel as described below.    
- To see the bot logs, create a channel called `bro-eater-logs` and give the bot permission to write in this channel.
- To use bot commands, add a BroMod role to the people who will operate it.
- Use the command `!brocommands` to list the bot's available commands.    

# Privacy Policy

Here is how Bro Eater deals with the information it has access to.

## What information does it have access to?

- Permission to read all messages in the channels it has access to (including text content and attachments). 
- Permission to read server channels (including but not limited to channel names and id). 
- Permission to read user data (such as user name, user id and messages sent by the user in the server channels).

## What is the information used for?

- The message content combined with the user information is analysed with the purpose to detect spam messages and decide whether messages should be deleted or not.
- The channel data is used to track where messages are being sent.   

## Is the data transmitted or stored?   

- Message content is kept in memory for a short while (less than a day) in order to analyse multiple messages sent by a user.
- None of the data analysed by Bro Eater is transmited to anywhere outside the application.
- Part of the data is stored in a log file (local) with the purpose of debugging the software:
  - Data stored in the log:
    - User id and user name that sent the messages
    - Attachment file names
    - Channel and time when the messages were sent
  - Data NOT stored in the log:
    - Attachment content
    - Message text content
- None of the data is used to train AI models.
- This data is subject to Square Cloud's Privacy Policy, as an operator of the application's content: https://squarecloud.app/pt-br/legal/privacy

## Can users opt out from having their data analysed?   

- Individual users cannot opt out. Since Bro Eater is a **moderation** bot based on message content, it's imperative that the bot has access to all messages sent in the channels it has permission to read.
- It's possible to deactivate the analysis in a server by using a specific bot command.
  - The bot will still see incoming messages, but will not take action or analyse the content. 
  - If the bot restarts due to technical reasons, the operation will be resumed automatically. This will be logged in the bot's log channel.

## Can the bot read my personal messages?   

- No, the bot can only read messages you send in channels where it has read permissions and messages that you send directly to the bot.   

