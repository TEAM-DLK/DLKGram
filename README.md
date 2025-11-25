

````html
<p align="center">
    <a href="https://github.com/TEAM-DLK/DLKGram">
        <img src="https://raw.githubusercontent.com/TEAM-DLK/DLKGram/main/assets/dlkgram-logo.png" alt="DLKGram" width="128">
    </a>
    <br>
    <b>Telegram MTProto API Framework for Python</b>
    <br>
    <a href="https://dlkgram.live">
        Homepage
    </a>
    •
    <a href="https://dlkgram.live/docs">
        Documentation
    </a>
    •
    <a href="https://t.me/DLKDevelopers">
        News
    </a>
    •
    <a href="https://t.me/DevDLK">
        Chat
    </a>
</p>

## DLKGram

> [!NOTE]
> The original Pyrogram is no longer actively maintained.  
> **DLKGram** is a modern fork by **TEAM-DLK**, with updated features and long-term support.

> Elegant, modern and asynchronous Telegram MTProto API framework in Python for users and bots.

```python
from pyrogram import Client, filters

app = Client("my_account")

@app.on_message(filters.private)
async def hello(client, message):
    await message.reply("Hello from DLKGram!")

app.run()
````

**DLKGram** is a modern, elegant and asynchronous
[MTProto API](https://core.telegram.org/mtproto) framework for Python.
It allows you to interact with Telegram using user accounts or bot accounts, with better performance and updated compatibility.

---

## 🚀 Why DLKGram?

* **Maintained**: Active support & updates by TEAM-DLK
* **Easy**: Simple API, same Pyrogram experience
* **Elegant**: Clean and modern codebase
* **Fast**: Powered by [TgCrypto](https://github.com/pyrogram/tgcrypto)
* **Async Ready**: Fully asynchronous (sync usage also supported)
* **Powerful**: Full Telegram MTProto API access

---

## 📦 Installation

### Stable version (PyPI)

```bash
pip install dlkgram
```

### Development version (GitHub)

```bash
pip install https://github.com/TEAM-DLK/DLKGram/archive/main.zip --force-reinstall
```

---

## 💡 Example

```python
from pyrogram import Client, filters

app = Client(
    "dlk_session",
    api_id=123456,
    api_hash="YOUR_API_HASH"
)

@app.on_message(filters.command("start"))
async def start(client, message):
    await message.reply("🔥 DLKGram is working perfectly!")

app.run()
```

---

## 🌍 Resources

* 📘 Documentation: [https://dlkgram.live/docs](https://dlkgram.live/docs)
* 📢 Updates Channel: [https://t.me/DLKDevelopers](https://t.me/DLKDevelopers)
* 💬 Support Chat: [https://t.me/DevDLK](https://t.me/DevDLK)
* 💻 GitHub: [https://github.com/TEAM-DLK/DLKGram](https://github.com/TEAM-DLK/DLKGram)

---

## ❤️ Support DLKGram

If you'd like to support this project:

* TON: `YOUR_WALLET_HERE`
* USDT TRC20: `YOUR_WALLET_HERE`

---

## ⚠️ Disclaimer

This project is an independent fork.
Not affiliated with the original Pyrogram developers.

Maintained with ❤️ by **TEAM-DLK**.


