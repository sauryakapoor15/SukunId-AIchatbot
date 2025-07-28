<h1 align="center"><b>🧠 Sᴜᴋᴜɴɪᴅ-ᴀɪ 🧠</b></h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=F77247&width=420&lines=𝙰+𝚃𝚎𝚕𝚎𝚐𝚛𝚊𝚖+AI+Chatbot+for+Groups+and+DM;𝙿𝚘𝚠𝚎𝚛𝚎𝚍+𝙱𝚢+𝚃𝚎𝚊𝚖+Sᴜᴋᴜɴ+❤️">
</p>

<p align="center">
  <img src="https://telegra.ph/file/ced98138e5e9e7c912098.jpg" width="400">
</p>

---

## 🚀 Features of SukunId-AI Bot

<details>
<summary><b>🧠 AI-Based Chatbot</b></summary>
<br>

- 🤖 **Auto Reply System** – Smart AI that remembers and replies using past data.
- 💬 **Works in Groups & Private Chats** – Responds to messages contextually.
- 🔒 **Admin-Only Control** – Only group admins can turn it on/off.
- 🧠 **Learns from Stickers & Text** – Bot stores replies with sticker IDs or text.
- 🔄 **Self-Learning Chatbot** – Train the bot by replying to its messages.
- 📦 **MongoDB Storage** – All training data is stored in MongoDB for long-term memory.
- 📍 **Dual Mode** – Distinct handling for private vs group chats.
</details>

---

## 🛠️ Commands Reference

<details>
<summary><b>👥 Group Commands</b></summary>
<br>

- `/chatbot` – Shows usage help (group only).
- `/chatbot on` – Enables chatbot in the group *(admin only)*.
- `/chatbot off` – Disables chatbot in the group *(admin only)*.
- `/hii` – Fun bot reply for interaction.
</details>

<details>
<summary><b>🙋 Private Chat Usage</b></summary>
<br>

- 📝 Send a message → Bot will respond with learned reply.
- 🧠 Reply to the bot’s message with new text/sticker → Bot learns the response.
- 📎 Stickers are handled just like text for learning & replying.
</details>

---

## ⚙️ Deploy This Bot

<details>
<summary><b>▶️ Deploy to Heroku</b></summary>
<br>

Click the button below to deploy on Heroku instantly:

<p align="center">
  <a href="https://heroku.com/deploy?template=https://github.com/TeamSukun/SukunId-AI">
    <img src="https://img.shields.io/badge/Deploy%20To-Heroku-purple?style=for-the-badge&logo=heroku" width="200"/>
  </a>
</p>

</details>

<details>
<summary><b>☁️ Deploy to Scalingo</b></summary>
<br>

<p align="center">
  <a href="https://my.scalingo.com/deploy?template=https://github.com/TeamSukun/SukunId-AI">
    <img src="https://cdn.scalingo.com/deploy/button.svg" width="220" />
  </a>
</p>

</details>

<details>
<summary><b>💻 Deploy on VPS</b></summary>
<br>

```bash
# Update packages
sudo apt update && sudo apt upgrade -y

# Install requirements
sudo apt install python3-pip ffmpeg -y
pip3 install -U pip

# Clone and run
git clone https://github.com/TeamSukun/SukunId-AI && cd SukunId-AI
pip3 install -U -r requirements.txt

# Add your env variables
cp sample.env .env
vi .env  # Press I to edit, then :wq to save

# Run bot
screen bash start
```
</details>

---

## 👑 Owner & Contributors

<details>
<summary><b>💖 Special Thanks To</b></summary>
<br>

- [Team Sukun](https://t.me/TeamSukun)
- Hyper King
- Kingabhinov
- [ᴀɴᴏɴʏᴍᴏᴜs](https://github.com/TheAnonymous2005)

</details>

---

## 📢 Support Channels

<details>
<summary><b>💬 Need Help?</b></summary>
<br>

<a href="https://telegram.dog/sukunupdates">
  <img src="https://img.shields.io/badge/Join-Telegram%20Channel-red.svg?logo=telegram">
</a>
&nbsp;
<a href="https://telegram.dog/sukunsupports">
  <img src="https://img.shields.io/badge/Join-Telegram%20Group-blue.svg?logo=telegram">
</a>

</details>

---


## 📚 Built With

<details>
<summary><b>🛠️ Technologies & Libraries Used</b></summary>
<br>

| Tool/Library     | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| 🐍 [Python](https://www.python.org/)             | Core programming language used to build the chatbot.             |
| 🤖 [Pyrogram](https://github.com/pyrogram/pyrogram)     | Telegram MTProto API Client Library for userbots and bots.       |
| 💬 [Telethon](https://github.com/LonamiWebs/Telethon)     | Python 3 Telegram MTProto API client library (optional or extra).|
| 🧠 [MongoDB](https://www.mongodb.com/)            | NoSQL database used to store user inputs, stickers, and replies. |
| ⚙️ [Motor](https://motor.readthedocs.io/)         | Async MongoDB driver for integration with Pyrogram bots.         |
| 🧪 [dnspython](https://www.dnspython.org/)        | DNS toolkit for Python, useful for MongoDB DNS URI parsing.      |
| 📡 [Requests](https://docs.python-requests.org/)  | HTTP library used for various external API interactions.         |
| 🔐 [tgcrypto](https://github.com/pyrogram/tgcrypto)     | Fast cryptographic operations for Pyrogram.                      |
| ☁️ [Heroku](https://heroku.com)                  | Cloud platform for fast and free bot deployment.                 |
| 🚀 [Scalingo](https://scalingo.com/)             | Another deployment platform for running Python bots.             |
| 🛠️ [Asyncio](https://docs.python.org/3/library/asyncio.html) | For asynchronous programming to improve performance.         |

</details>
