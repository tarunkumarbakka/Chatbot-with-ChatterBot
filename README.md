# 🤖 ChatterBot: Build a Chatbot with Python

This project demonstrates how to build a **self-learning chatbot** using **Python** and the **ChatterBot** library. The chatbot learns from user input in real time, improves its responses with continued use, and stores its training data in a local SQLite database.
---

## 🧠 Features

- Trainable, self-learning chatbot
- Interactive CLI-based conversation
- SQLite database-backed learning memory
- Easily customizable conversation training logic
- Minimal dependencies using `pip` and `venv`

---

## 🚀 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/tarunkumarbakka/Chatbot-with-ChatterBot.git
cd Chatbot-with-ChatterBot

Create and activate a [virtual environment](https://realpython.com/python-virtual-environments-a-primer/), then install the necessary dependencies:

```sh
$ python -m venv venv
$ source venv/bin/activate
(venv) $ python -m pip install -r requirements.txt
```

Then you can navigate into the folder `source_code_final/` and train and start the interactive command-line interface chatbot by running `bot.py`:

```sh
(venv) $ cd source_code_final
(venv) $ python bot.py
```

After training, you'll see an interactive prompt that you can chat with:

```text
> hi
🪴 Welcome, friend 🤗
> thanks for the green welcome
🪴 I let you
> you let me be here?
🪴 It's a monsters!
> did you mean monstera?
🪴 The leafs that she had are getting dryer and dryer. But she’s also growing plenty of new ones
> who?
🪴 Do raindrops touch their leaves?
> very philosophical!
🪴 Lol
> ;)
🪴 I don't grow any crop at home
> no crops in pots
🪴 Ah, gotcha!
```

The bot will learn from the replies you give and improve its accuracy. You can quit the interactive prompt by typing any of the `exit_conditions` defined in `bot.py`.

📂 Project Structure
Chatbot-with-ChatterBot/
├── source_code_final/
│   ├── bot.py
│   ├── db.sqlite3
├── requirements.txt
├── README.md

🧾 License
This project is licensed under the MIT License.
