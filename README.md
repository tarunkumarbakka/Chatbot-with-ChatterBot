# 🤖 ChatterBot: Build a Chatbot with Python

This project demonstrates how to build a self-learning chatbot using Python and the ChatterBot library. The chatbot learns from user input in real time, improves its responses with continued use, and stores its training data in a local SQLite database.

---

## 🧪 Features

* Trainable, self-learning chatbot
* Interactive CLI-based conversation
* SQLite database-backed learning memory
* Easily customizable conversation training logic
* Minimal dependencies using pip and venv

---

## 🚀 Installation & Setup

### 1. Clone the repository

```sh
git clone https://github.com/tarunkumarbakka/Chatbot-with-ChatterBot.git
cd Chatbot-with-ChatterBot
```

### **2. Create and activate a virtual environment**

```sh
python -m venv venv

# On Windows
venv\Scripts\activate

# On macOS/Linux
source venv/bin/activate
```

### 3. Install Dependencies

```sh
pip install -r requirements.txt
```

---

## 💬 Run the Chatbot

Navigate into the folder `source_code_final/` and train/start the chatbot by running `bot.py`:

```sh
cd source_code_final
python bot.py
```

After training, you'll see an interactive prompt that you can chat with:

```text
> hi
🍵 Welcome, friend 🤗
> how are you?
🍵 I'm doing well, thank you!
> bye
🍵 See you soon!
```

The bot will learn from the replies you give and improve its accuracy. You can quit the prompt by typing any of the `exit_conditions` defined in `bot.py`.

---

## 📂 Project Structure

```
Chatbot-with-ChatterBot/
├── source_code_final/
│   ├── bot.py
│   ├── db.sqlite3
├── requirements.txt
├── README.md
```
---

## 📄 License

This project is licensed under the **MIT License**.
