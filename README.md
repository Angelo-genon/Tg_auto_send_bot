# 🇵🇭 TG AUTO SEND BOT 🇵🇭
## Created by: Angelo Genon

### Description
This bot automatically scrapes images from a specified URL and sends them to a Telegram group.

### Installation

1. **Install Termux**:
   - Download Termux from the [Play Store](https://play.google.com/store/apps/details?id=com.termux) or [F-Droid](https://f-droid.org/packages/com.termux/).

2. **Open Termux** and run these commands:

    ```bash
    termux-setup-storage
    apt update && apt upgrade -y
    pkg install git python3 python-pip php openssh -y
    pip3 install requests beautifulsoup4 aiogram
    ```

3. **Clone this repository**:

    ```bash
    git clone https://github.com/angelo-genon/tg_auto_send_bot.git
    cd tg_auto_send_bot
    ```

4. **Run the setup script**:

    ```bash
    python3 setup_menu.py
    ```

5. **Run the bot**:

    ```bash
    python3 tg_auto_send_bot.py
    ```

### License
For educational purposes only. Use responsibly.