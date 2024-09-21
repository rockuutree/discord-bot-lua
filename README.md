# Discord Bot Lua Obfuscator (Python 3.7.9)

## About
This is a simple Discord bot written in Python for obfuscating Lua files sent by users in a specific channel (also works in direct messages). It's useful for securing your Lua scripts, compatible with FiveM/Roblox and other resources.

This version has been modified to work with Repl.it and Heroku for easy deployment.

## Features
- Obfuscates Lua files sent in Discord
- Works in specific channels and direct messages
- Compatible with FiveM/Roblox resources
- Easy deployment on Repl.it and Heroku

## Required Python Modules
- Discord.py
- requests
- Flask

## Heroku Deployment Guide
1. Fork this repository
2. Create an app on Heroku
3. Go to Deploy -> GitHub and connect your account
4. Enter the repository name
5. Enable Automatic Deploys, then Deploy Branch
6. Go to Settings -> Reveal Config Vars
7. Add `DISCORD_TOKEN` to the environment variables
8. Your bot is now deployed and ready to use

## Usage
Send a Lua file in the designated Discord channel or via DM to the bot, and it will respond with an obfuscated version of the script.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is open source and available under the [MIT License](LICENSE).

## Acknowledgements
- Original code by [yunglean4171](https://github.com/yunglean4171)
- Modified for Repl.it and Heroku by [jmesfo0](https://github.com/jmesfo0)# discord-bot-lua
# discord-bot-lua
