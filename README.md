# GoGPTDiscord

GoGPTDiscord is a Discord chat bot written in Go, leveraging the power of OpenAI's ChatGPT API to provide engaging and informative conversations. It uses Go 1.18 and the discordgo library for connecting to Discord.

## Installation
1. Ensure you have Go 1.18 or later installed on your system. You can download it from the official Go website.

2. Clone this repository:
```
git clone https://github.com/karantan/GoGPTDiscord.git
```
3. Change to the project directory:
```
cd GoGPTDiscord
```
4. Install the required dependencies:
```
go mod download
```

## Usage

1. Create a new Discord bot and obtain its token by following the instructions in the Discord Developer Portal.

2. Set the `DISCORD_BOT_TOKEN` and `OPENAI_API_KEY` environment variables with your Discord bot token and ChatGPT API key, respectively.

```
export DISCORD_BOT_TOKEN=your_discord_bot_token
export OPENAI_API_KEY=your_openai_api_key
```

3. Build and run the bot
```
go build
./GoGPTDiscord
```

4. Invite the bot to your Discord server using the link provided by the Discord Developer Portal.

5. The bot is now ready! Interact with it by mentioning it in a text channel or sending it a direct message.

## Contributing
Contributions are welcome! If you'd like to improve the GoGPTDiscord bot or fix any issues, please follow these steps:

1. Fork the repository on GitHub.
1. Create a new branch for your changes.
1. Commit your changes, ensuring you follow the Go coding standards.
1. Push your changes to your fork.
1. Submit a pull request.


## License
GoGPTDiscord is released under the BSD 3-Clause License.
