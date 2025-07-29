Got it! Here's a beautifully styled **README.md** content presented as **plain text (not markdown)** — just like you'd see it rendered on GitHub, but outside of markdown formatting:

---

# 🚖 HamSafar Bot – Telegram Ride-Sharing Assistant

**HamSafar Bot** is a simple and smart Telegram bot designed to connect **drivers** and **passengers** for intercity or regional travel. Whether you're offering a ride or looking for one — HamSafar makes it easier to find your travel partner!

---

## 📌 Features

### 👨‍✈️ For Drivers

Drivers can:

* 🚗 Add a route by specifying:

  * From where to where
  * Contact phone number
  * Number of available seats
* 📩 Receive ride requests from passengers
* ✅ Accept or ❌ Decline ride requests

  * Accepted requests reduce available seats
  * Once all seats are taken, the route is **automatically removed**

### 🧍 For Passengers

Passengers can:

* 🔍 View all available routes
* 📤 Send a request to join a chosen ride
* 💬 Receive confirmation or rejection from the driver via the bot

---

## ⚙️ Installation & Setup

1. 🔁 Clone the repository:
   git clone [https://github.com/your-username/hamsafar-bot.git](https://github.com/your-username/hamsafar-bot.git)
   cd hamsafar-bot

2. 🧪 Create a virtual environment:
   python -m venv .venv
   source .venv/bin/activate  (Windows: .venv\Scripts\activate)

3. 📦 Install dependencies:
   pip install -r requirements.txt

4. 🔐 Create a config file:
   Create a file named `config.py` in the root folder and add:
   BOT\_TOKEN = 'your-telegram-bot-token'

5. ▶️ Run the bot:
   python main.py

---

## 💾 Technology Stack

* Python
* Aiogram 3.x
* SQLite

---

## 🌐 How It Works

Driver adds route → Bot saves info → Passenger views routes → Sends request →
Driver accepts or declines → Bot informs passenger → Seats update →
If full, route is removed.

---

## 🇹🇯 Made for Tajikistan – but works anywhere

This project is inspired by the real needs of regional travel coordination in Tajikistan, but it’s suitable for any area where people use Telegram.

---

## 📬 Contact

**Created by:** Shamsiddin
For questions or collaboration, feel free to reach out via Telegram or GitHub.

---

Let me know if you'd like a **Tajik version** or a `.md` file export of this.
