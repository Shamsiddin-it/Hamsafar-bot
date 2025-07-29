````markdown
# 🛻 HamSafar Bot – Telegram Bot for Ride Sharing

**HamSafar** is a Telegram bot that helps passengers and drivers connect for taxi rides from one region to another.

## 🔧 Features

### 👨‍✈️ Driver
Drivers can:
- Add a new route by providing:
  - Departure location
  - Destination
  - Phone number
  - Number of available seats
- Receive ride requests from passengers
- Accept or decline passenger requests
  - If **accepted**, available seats decrease
  - If no seats remain, the route is removed automatically

### 🧍 Passenger (Client)
Passengers can:
- View all available routes
- Send a request to join a specific ride
- Receive confirmation if the driver accepts

## ⚙️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/hamsafar-bot.git
cd hamsafar-bot
````

### 2. Create virtual environment

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Create `config.py`

Inside the project root, create a file named `config.py` with the following content:

```python
BOT_TOKEN = 'your-telegram-bot-token-here'
```

### 5. Run the bot

```bash
python main.py
```

## 💾 Database

This bot uses **SQLite** for local data storage. The database file will be created automatically when the bot runs for the first time.

## 📌 Notes

* Built with [Aiogram 3.x](https://docs.aiogram.dev/)
* Works for ride coordination within Tajikistan or any region where drivers and passengers communicate via Telegram

## 📞 Contact

For any questions, please contact the project owner: **Shamsiddin**

---

