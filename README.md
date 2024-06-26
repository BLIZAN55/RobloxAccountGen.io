# RobloxAccountGen.io
# Roblox Account Generator

This is a simple Node.js script to automate the creation of Roblox accounts. It utilizes the Playwright library for browser automation.

## Prerequisites

- Node.js installed on your system.
- Basic knowledge of JavaScript and Node.js.

## Setup

1. Clone this repository to your local machine.
2. Install dependencies by running `npm install`.

## Usage
1. Ensure you have an available email address that is not linked to an existing Roblox account.
2. Run the script using `npm start`.
3. The script will create Roblox accounts with random credentials and store them in the specified file.
   
## Configuration

You can customize the script by modifying the following variables in the `config.js` file:
- `MIN_AGE`: Minimum age for account creation.
- `MAX_AGE`: Maximum age for account creation.
- `MAX_PASSWORD_LENGTH`: Maximum length for generated passwords.

## Note

- If the `config.json` and or the `Accounts.json` file does not exist, it will be auto-generated by the script as then you will be able to edit the config.
- Make sure to use an email address that is not already linked to a Roblox account.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

