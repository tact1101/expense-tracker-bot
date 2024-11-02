# Expense Tracker Telegram Bot

![Python Version](https://img.shields.io/badge/python-3.9%2B-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## Description
A Telegram bot to help users track their expenses, categorize them, and visualize data with histograms. Utilizes PostgreSQL for persistent storage and Redis for caching.

## Features
- User authentication
- Custom expense categories
- Monthly expense summaries
- Visualization of expenses over time
- Rate limiting and error handling for API requests

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/username/expense-tracker-bot.git
    ```
2. Navigate into the project directory:
    ```bash
    cd expense-tracker-bot
    ```
3. Create a virtual environment:
    ```bash
    python -m venv venv
    ```
4. Activate the virtual environment:
    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```bash
      source venv/bin/activate
      ```
5. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Set up your Telegram bot using [BotFather](https://core.telegram.org/bots#botfather) and obtain the API token.
2. Update the `config.py` file with your bot token and database credentials.
3. Run the bot:
    ```bash
    python bot/bot.py
    ```

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [Telegram Bot API](https://core.telegram.org/bots/api)
- [PostgreSQL](https://www.postgresql.org/)
- [Redis](https://redis.io/)