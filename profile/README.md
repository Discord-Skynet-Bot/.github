# Skynet Bot

Skynet Bot is a powerful and feature-rich Discord bot created exclusively for the Media Void Community. With careful consideration of our community's unique requirements, Skynet Bot has been developed from scratch as a passion project to ensure it perfectly aligns with our needs. By consolidating functionalities from various other bots, Skynet Bot offers a comprehensive and centralized solution for all our Discord server needs.

## Features

Skynet Bot comes equipped with an extensive range of features designed to enhance our community's Discord experience. Some of the key features include:

- Feature 1

- Feature 2 

- Feature 3

## Contributing

We highly appreciate contributions from our dedicated and active members within the Media Void Community. If you wish to contribute to the ongoing development and enhancement of Skynet Bot, kindly follow the guidelines provided below:

1. Fork the Skynet Bot repository to your personal GitHub account.
2. Create a new branch in your forked repository to isolate your specific contribution.
3. Implement your changes while adhering to the existing coding style and guidelines.
4. Thoroughly test your changes to ensure they function as intended and do not introduce any regressions.
5. Commit and push your changes to your forked repository.
6. Submit a detailed pull request, clearly explaining the purpose and impact of your contribution.

Please note that currently, contributions to Skynet Bot are limited to active members of the Media Void Community. We believe that the valuable insights and first-hand experience of our community members will play a crucial role in shaping the future development of the bot, aligning it with our collective interests.

It is important to mention that the repository is set to private, and access is granted exclusively by the leadership team, specifically the Community Managers. Reach out to them to request access and contribute to Skynet Bot.

## Wiki

We are in the process of developing a comprehensive Wiki that will provide detailed documentation on all the features and functiTo facilitate seamless usage of Skynet Bot and its various features, we are actively developing a comprehensive Wiki and documentation. The Wiki will serve as a central hub of information, providing detailed explanations, step-by-step guides, and troubleshooting assistance. We encourage all members to refer to the Wiki for any inquiries or assistance regarding Skynet Bot.onalities of the Skynet Bot. The Wiki will serve as a valuable resource for understanding how to use the bot effectively.

## Web-Based Application

As part of our commitment to continuously enhance the user experience, we are currently in the process of developing a web-based application that will complement To further elevate the user experience, we are actively developing a web-based application that seamlessly integrates with Skynet Bot. This application will serve as an additional interface, offering enhanced functionality and accessibility for administrators, moderators, and select roles within our server. With the web interface, authorized members will have the ability to effortlessly manage commands, customize options, and make necessary adjustments directly within the server. Stay tuned for updates on this exciting development as we strive to empower our community with even greater control and flexibility.the functionality of Skynet Bot. This application will provide an alternative interface and additional features, allowing members to interact with the bot effortlessly using a web browser. Stay tuned for updates on this exciting development!

## Installing and Running the Bot Locally

To install and run Skynet Bot locally, please follow these steps:

1. Clone the Skynet Bot repository to your local machine:
	```
	git clone https://github.com/Discord-Skynet-Bot/Skynet-Bot.git
	```
2. Navigate to the project directory:
	``` 
	cd Skynet-Bot
	```
3. Install the required dependencies using either npm or yarn:
	```npm install` or `yarn install```
4. Create a `.env` file in the root directory of the project.
5. Open the `.env` file and add the following environment variables:
	```
	TOKEN=your_discord_bot_token_here
	PREFIX=your_desired_bot_prefix_here
	```
Replace `your_discord_bot_token_here` with the token of your Discord bot, and `your_desired_bot_prefix_here` with the prefix you want to use for the bot's commands.

**Note**: The `.env` file is used to store sensitive information and should not be shared publicly. Make sure to add it to your `.gitignore` file to prevent it from being committed to version control.

6. Save the `.env` file.
7. Run the bot using the following command:
	```
	npm start
	```
The bot will now be online and ready to serve your Discord server.

**Note**: Make sure your bot has been invited to your Discord server before running it.

To invite your Discord bot to a server through the Discord Developers app, follow these steps:

1. Go to the [Discord Developers Portal](https://discord.com/developers) and log in with your Discord account.
2. Select your bot application from the list or create a new one if you haven't already.
3. In the left-hand menu, click on "OAuth2" to access the OAuth2 settings.
4. Under the "Scopes" section, select the "bot" checkbox. This will generate a new URL in the "Scopes" box.
5. Scroll down to the "Bot Permissions" section and select the necessary permissions that your bot requires for its functionality. The required permissions may vary depending on the features and commands used by your bot.
6. Once you have selected the desired permissions, the URL in the "Scopes" box will be automatically updated.
7. Copy the updated URL and open it in your web browser.
8. You will be prompted to select a server where you want to invite your bot. Choose the server from the drop-down menu and click "Authorize" to grant the bot access to the selected server.
9. Complete any additional verification steps if prompted by Discord.
10. After successfully authorizing the bot, it will be added to the selected server, and you will see it listed in the server's member list.

By following these steps, you can invite your Discord bot to a server using the Discord Developers app.

## Updating .env

If you need to update the values in your .env file, follow these steps:

- Open the `.env` file in the root directory of the project.
- Update the values of the environment variables as needed.
- Save the `.env` file.
- Restart the bot for the changes to take effect.

**Note**: If the bot is already running, you will need to stop it and start it again with the updated values in the `.env` file.

By following these steps, you should be able to successfully install and run Skynet Bot on your local machine.

## Dependencies

Skynet Bot has the following dependencies:

- __discord.js__: A powerful JavaScript library for interacting with the Discord API.
- __dotenv__: A module that loads environment variables from a `.env` file into `process.env`.

These dependencies will be automatically installed when you follow the installation instructions mentioned earlier. The required versions of these dependencies are specified in the `package.json` file of the project.

Make sure you have a compatible version of Node.js installed on your machine to run the bot successfully.

For more details about the dependencies and their usage, refer to their respective documentation.

Please note that all the required dependencies will be installed automatically when you run the `npm install` or `yarn install` command as part of the installation process.

## Contact

For any questions, suggestions, or feedback related to Skynet Bot, please don't hesitate to reach out to our dedicated support team on the Media Void Community Discord server. We are committed to providing timely assistance and ensuring that Skynet Bot remains a valuable asset for our community.
