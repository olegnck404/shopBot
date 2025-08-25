# shopBot

A Telegram bot for managing a simple online store.

## Features

- Product catalog browsing
- Adding items to the cart
- Order processing and management
- User authentication and session handling

## Installation

1. Clone the repository:
```
git clone https://github.com/olegnck404/shopBot.git
cd shopBot
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Set up your Telegram bot and obtain the API token.

4. Configure the bot with your token and database settings in the appropriate files.

5. Run the bot:
```
python main.py
```

## Files Overview

- `main.py`: Entry point of the bot.
- `handlers.py`: Contains functions for handling user interactions.
- `keyboards.py`: Defines custom keyboards for the bot.
- `states.py`: Manages user states and transitions.
- `db.py`: Handles database operations.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `requirements.txt`: Lists the Python dependencies.

## Contributing

Contributions are welcome. Please fork the repository, create a new branch, and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
