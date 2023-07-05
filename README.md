# CHICBOT
-CHICBOT
-CHICBOT is a Discord bot developed using the discord.js library,
designed to enhance server functionality and provide an engaging user experience. 
The bot offers several commands and features, including NFT validation and voice channel access control.

-Features
Hello Command: Interact with the bot by using the !hello command. 
It will respond with a friendly greeting message.

-Ping Command: Test the bot's responsiveness by using the !ping command. 
It will reply with a "Pong!" message.

-Say Command: Use the !say command to make the bot send a message in the current channel.
Include the desired text after the command.

-ButtonClicked Command: This command utilizes NFT validation to control access to a designated voice channel. 
Players who possess a specific NFT will be granted access to the voice channel by using the !buttonClicked command.

-Prerequisites
Node.js: Make sure you have Node.js installed on your machine.

-Discord Bot Token: Obtain a Discord bot token by creating a new bot on the Discord Developer Portal.

-Installation
Clone the repository or download the source code.

-Install the dependencies by running the following command in the project directory:
npm install
-Set your Discord bot token by replacing BOT_TOKEN in the client.login() method with your actual token.

-Run the bot using the following command:
node bot.js

-Usage
Once the bot is up and running, invite it to your Discord server using the provided OAuth2 URL.
Ensure that the bot has the necessary permissions to function properly.

-Use the available commands in your Discord server to interact with the bot.
For example, you can type !hello to receive a greeting from the bot or !ping to test its responsiveness.

-The !buttonClicked command is specifically designed to grant access to a voice channel based on NFT ownership. 
Make sure to customize the NFT contract address and token ID in the checkHasNFT() function to match your specific requirements.

-Contributing
Contributions to CHICBOT are welcome! If you have any suggestions, bug reports, or feature requests,
please feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.

Feel free to customize this README.md file to include more details, additional sections, or any specific instructions relevant to your CHICBOT Discord bot.
