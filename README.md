# ServerMaid!
Discord bot for managing the total number of messages allowed in the channel provided.

# Setup
Edit the .env file and replace "YOUR BOTS TOKEN" with ofc, your bots token.
You can use notepad++ to edit the file.

# What the hoo ha is goin' on..
When the bot is invited to the server you can then use the commands to have it monitor any channel you wish and set a number of max messages allowed in the channel. It will delete any messages once that cap is met and new messages appear starting at the oldest. Good for bot cmd channels and whatnot.

Any command sent to monitor a channel will save to the server_databse (can be in multiple servers) so that if the bot goes offline ever, when started again it will still know what channels to monitor.

Make sure to give the bot proper permission to use slash commands and manage channels.

It is set up to handle a good number of servers, but I couldn't fix the rate limit! Goodluck!
