## 📛 TikTok Mass Reporter

![Screenshot 2025-06-15 182357](https://github.com/user-attachments/assets/97088490-65d4-4ca5-a9b0-077f4456949a)


![License](https://img.shields.io/badge/license-MIT-green.svg)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)

> **Disclaimer:** This tool is for **educational** and **research** purposes **only**. Do **not** use this to harass or attack other users. The author is not responsible for any misuse or legal consequences.

---

### 🚀 Features

* Multi-threaded TikTok report submission
* Proxy support (auto-fetched from ProxyScrape)
* Pre-defined report reason codes
* Real-time logging and status tracking
* Stylish CLI with animated banners and colored output

---

### 📦 Requirements

* Python 3.8+
* `tls_client`, `httpx`, `requests`, `fade`

Install dependencies:

```bash
pip install tls_client httpx requests fade
```

---

### ⚙️ Configuration

Create a `config.json` in the same directory:

```json
{
  "proxy": ""  // leave blank to use proxies.txt, or provide a single proxy string
}
```

You must also have a `proxies.txt` file in the root directory. The program will overwrite it automatically when it runs.

---

### 🧠 Usage

```bash
python main.py
```

Follow the on-screen prompts:

1. Enter number of threads
2. Enter TikTok report URL
3. Select report reason from the numbered list

---

### 📂 File Structure

```bash
.
├── main.py           # Main script
├── config.json       # Your configuration file
├── proxies.txt       # Automatically generated proxy list
└── README.md         # You're reading this
```

---

### 🛑 Warning

**Misuse of this software is strictly prohibited.**

* Using mass reporting tools violates platform TOS.
* This tool is designed for research, red teaming, and educational analysis.
* You are fully responsible for any actions taken using this code.

---

### 📝 License

MIT License. See `LICENSE` file for more details.

---
