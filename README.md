# 💬 Telegram Chat Button – WordPress Plugin

---

Easily add a **Telegram chat button** to your WordPress website.  
This plugin lets visitors contact you directly via Telegram — with **mobile app or desktop browser auto-detection**.  
It works anywhere on your site using a simple `[telegram_chat]` shortcode.

---

## 🚀 Features

✅ Works on both **mobile and desktop**  
✅ Automatically opens **Telegram app** on mobile devices  
✅ Customizable **username**, **message text**, and **button label**  
✅ Supports **custom colors** for button and text  
✅ Simple **shortcode** – no coding required  
✅ 100% lightweight, no external dependencies  

---

## ⚙️ Installation

1. Download or clone this repository:
   ```bash
   git clone https://github.com/hulviseth/telegram_chat.git
````

2. Upload the folder to your WordPress installation:

   ```
   /wp-content/plugins/telegram_chat
   ```

3. Go to **Dashboard → Plugins → Installed Plugins**
   and activate **Telegram Chat Button**.

---

Notes, behavior & tips

The plugin uses the tg://resolve?domain=USERNAME&text=... scheme which opens the Telegram app on mobile. If the app is not installed or the scheme fails, a fallback to https://t.me/USERNAME?text=... is used.

The button looks like a normal link (no 3rd-party CSS). You can add your own classes via the class attribute in the shortcode and style it with theme CSS if desired.

The message is URL-encoded on output to avoid breaking links.

The admin page is optional — you can set defaults there and override via shortcode attributes.

No external JavaScript libraries, no external CSS, no requests to third-party servers — fully local and lightweight.

Examples

Basic: [telegram_chat username="acme_support" label="Chat" message="Hi, I want help"]

With colors: [telegram_chat username="myname" label="Chat on Telegram" btn_color="#2AABEE" text_color="#fff" message="Hello there"]

Extra class/id: [telegram_chat username="myname" label="Support" class="my-chat-btn" id="chat-top"]

---

## 🛠️ Technical Details

* Compatible with **WordPress 5.0+**
* Supports **PHP 7.4 – 8.3**
* Uses a lightweight JavaScript user-agent detection
* No external scripts or dependencies

---

## 🧑‍💻 Author

**R VISETH HUL**
🌐 [howting I like ](https://hostinger22.duoservers.com/)

---

## 📄 License

This plugin is licensed under the **GPL-2.0 License**.
You are free to modify and redistribute it under the same license.

---


---

```

---


