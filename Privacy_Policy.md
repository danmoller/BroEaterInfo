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
