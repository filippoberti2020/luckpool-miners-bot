# LuckPool Telegram Bot

This is the official bot of LuckPool to monitor your crypto mining worker. LuckPool is a unique mining pool that offers a variety of features, including Miner's Jackpot, Hybrid Solo Mining, and PPLTS-based reward system. The pool also supports XtraNonce, custom minimum payment, and custom desired stratum mining difficulty.

## Features

- Save and manage your wallet address linked to your Telegram user.
- Use the `/info` command to get stats from your mining worker by scraping data from [LuckPool's mining worker page](https://luckpool.net/verus/miner.html?<walletaddress>).
- Fastest mining servers in NA, EU, and AP.
- Anonymous mining; NO SIGNUP!
- Dedicated servers, NO VPS!
- Low Pool Fee (1%).

## Getting Started

1. **Save your wallet address**: Use the `/save_link` command to save your wallet address. You can optionally provide a name for your link.

    ```
    /save_link <name> <walletaddress>
    ```

2. **Get stats from your mining worker**: Use the `/info` command to get stats from your mining worker.

    ```
    /info <walletaddress>
    ```

## Installation

1. **Clone the repository**:

    ```
    git clone https://github.com/<username>/luckpool-telegram-bot.git
    ```

2. **Install the required packages**:

    ```
    pip install -r requirements.txt
    ```

3. **Create a `.env` file**:

    ```
    TELEGRAM_BOT_TOKEN=<your_bot_token>
    DATABASE_URL=<your_database_url>
    ```

4. **Run the bot**:

    ```
    python main.py
    ```

## Contributing

Contributions are welcome! If you have any suggestions or issues, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Resources

- [LuckPool Official Website](https://luckpool.net)
- [LuckPool Verus Mining Pool](https://luckpool.net/verus/)
- [LuckPool Mining Worker Page](https://luckpool.net/verus/miner.html)
- [LuckPool Connect Page](https://luckpool.net/verus/connect.html)
