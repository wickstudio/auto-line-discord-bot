# Auto Line Discord Bot

## Description
This Discord bot automatically sends a predefined image to specific channels. Administrators can add or remove channels from the auto line feature using the `!line` command.

## Setup and Installation

### Prerequisites
- Node.js
- npm (Node.js package manager)
- A Discord account and a bot token

### Installation Steps
1. **Clone the Repository**: Clone this repository to your local machine or download the source code.
2. **Install Dependencies**:
   - Run `install.bat` by double-clicking the file. This will install the required dependencies.
3. **Configuration**:
   - Fill in your bot token and the image URL in `config.json`.
   - Create an empty `channels.json` file or use the provided template.

### Running the Bot
- To start the bot, double-click the `start.bat` file. This will execute the bot using Node.js.

## Usage
- **Adding a Channel**: Use the `!line` command in any channel where you want the bot to start sending the image. The bot will automatically add this channel to its list.
- **Removing a Channel**: Use the `!line` command again in a channel that's already in the list to remove it.
- **Auto Line Feature**: The bot will automatically send the specified image in all channels that are in the auto line list.

## Contributing
Contributions to the bot are welcome. Please feel free to fork the repository, make changes, and create a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For any queries or suggestions, please join discord server [ https://discord.gg/NFh7xtMNz2 ].
