# TerminalBOT

**Telegram Bot with Command Line Interface**

TerminalBOT is a Telegram bot that allows users to interact with their system's command line interface (CLI) directly from Telegram. Users can execute various commands like listing files, changing directories, displaying file content, creating directories, cloning git repositories, running Python scripts, installing Python packages via pip, and running shell commands.

## Features

- **/start**: Start the bot and receive a welcome message with instructions.
- **/help**: Get a list of available commands along with their descriptions.
- **/ls**: List files in the current directory.
- **/pwd**: Show the current directory path.
- **/cd [directory]**: Change directory to the specified one.
- **/cat [file_path]**: Display the content of a file.
- **/mkdir [directory_name]**: Create a new directory.
- **/git_clone [repository_url]**: Clone a git repository.
- **/run_python [script_path]**: Run a Python script.
- **/run_pip [package1] [package2] ...**: Install Python packages via pip.
- **/shell [command]**: Run shell commands.

## Additional Features

- **Error Handling**: The bot handles errors gracefully and provides informative error messages if a command fails to execute.
- **Markdown Support**: Responses are formatted in Markdown for better readability.
- **Security Considerations**: Ensure to restrict sensitive commands and limit the scope of operations the bot can perform to avoid potential security risks.
- **Interactive Feedback**: The bot provides interactive feedback on command execution status, making the user experience more engaging and informative.
- **Permission Control**: Implement permission control mechanisms to restrict access to certain commands based on user roles or privileges.
- **Logging**: Implement logging to track bot activities and troubleshoot issues effectively.
- **User Authentication**: Add user authentication mechanisms if required to ensure only authorized users can interact with the bot.
- **Command History**: Implement a command history feature to allow users to recall previously executed commands.

## Getting Started

1. **Clone the Repository**: Clone the repository to your local machine.

    ```bash
    git clone https://github.com/AnonAmit/TerminalBOT.git
    ```

2. **Set up Environment**: Ensure Python and required dependencies are installed.

    ```bash
    pip install -r requirements.txt
    ```

3. **Set up Telegram Bot**: Create a new bot on Telegram using BotFather and obtain your bot token.

4. **Set Environment Variable**: Set your Telegram bot token as an environment variable named `TELEGRAM_BOT_TOKEN`.

    ```bash
    export TELEGRAM_BOT_TOKEN="your_bot_token"
    ```

5. **Run the Bot**: Execute the `main()` function to start the bot. Your bot is now operational and ready to receive commands from Telegram users.

    ```bash
    python bot.py
    ```


## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/AnonAmit/TerminalBOT/blob/main/LICENSE.sql) file for details.

Made by [ANONYMOUS_AMIT](https://t.me/ANONYMOUS_AMIT)
