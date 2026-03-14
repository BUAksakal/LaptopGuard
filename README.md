# LaptopGuard

Minimal laptop security monitor that detects charger disconnection and sends an alert.

LaptopGuard is a lightweight Python desktop application that continuously monitors your laptop’s power connection.  
If the charger is unplugged, the system immediately triggers a desktop notification and sends a Telegram alert.

This project demonstrates practical Python development including system monitoring, GUI development, and API integration.

## Features

- Real-time charger disconnection detection
- Telegram alert notifications
- Desktop popup notifications
- Modern GUI using CustomTkinter
- Lightweight and easy to run

---

## Technologies

- Python
- psutil
- CustomTkinter
- Telegram Bot API
- plyer notifications
- requests

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/LaptopGuard.git
cd LaptopGuard
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python main.py
```

---

## Configuration

Before running the application, update the Telegram configuration inside the script:

```python
BOT_TOKEN = "YOUR_TELEGRAM_BOT_TOKEN"
CHAT_ID = "YOUR_CHAT_ID"
```

You can create a Telegram bot using **@BotFather** on Telegram.

---

## Project Structure

```
LaptopGuard
│
├ main.py
├ requirements.txt
├ README.md
```

---

## Example Use Case

LaptopGuard can help detect potential laptop theft attempts in environments such as:

- libraries
- cafés
- universities
- co-working spaces

If someone disconnects the charger while you are away, the system immediately sends an alert.

---

## Future Improvements

- Webcam photo capture when charger is disconnected
- Motion detection
- System tray integration
- Alarm sound
- Auto start with operating system

---

## License

MIT License
