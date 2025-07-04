# Chess Username Sniper

A fast, threaded username availability checker for Chess.com, with optional Discord webhook batch notifications.  
Designed to efficiently scan and notify about available Chess.com usernames.

---

## Features

- Checks username availability on Chess.com via public API  
- Threaded to improve checking speed  
- Avoids re-checking known usernames (saves results locally)  
- Optional Discord webhook notifications in configurable batch sizes  
- ASCII art splash screen on start  
- Configurable username length and batch size

---

## Requirements

- Python 3.7+  
- pip package manager  
- requests library  

---

## Setup & Installation

1. Clone the repository:

```bash
git clone https://github.com/Dansvn/chess-username-sniper
cd chess-username-sniper
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the script:

```bash
python main.py
```

---

## Usage

- Enter the desired username length and batch size.  
- Choose whether to use a Discord webhook for notifications.  
- The script checks username availability on Chess.com in batches with threading.  
- Available usernames are saved in `available.txt` and taken ones in `taken.txt`.  
- If enabled, notifications are sent to your Discord webhook in batches.

---

## About

Chess Username Sniper is a utility project aimed to help find available Chess.com usernames quickly.  
No guarantee of uptime or official support.

---

## Contact

For questions or feedback, reach out at:  
[https://ayo.so/dansvn](https://ayo.so/dansvn)

