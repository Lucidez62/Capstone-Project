
# 🔍✨ Log Analyzer Extension with PDF Steganography

> ✅ _Analyze anomalous web server logs like a pro_  
> 📄 _Hide AI-generated solutions inside PDFs using invisible whitespace_  
> 🧠 _AI-powered suggestions. Stealthy. Elegant. Efficient._

---

## 🚀 Overview

This browser extension revolutionizes how anomalies in web server logs are handled. It not only **detects and analyzes anomalies** using advanced AI techniques, but it also **embeds the solution invisibly** into a PDF report using **whitespace-based steganography** (spaces = `0`, tabs = `1`). This allows you to:

- 📊 Auto-analyze log anomalies via a professional frontend  
- 🤖 Get intelligent solution suggestions from an AI backend (Cohere or local)  
- 📄 Export a PDF with hidden fixes embedded (visible only to your decoding system)

> 💡 Imagine sharing logs with solutions already inside — but hidden. That's the power of stealthy AI debugging.

---

## 🧩 Features

✅ **Stylish Non-React Frontend**  
✅ **Automatic Anomaly Detection**  
✅ **AI-Powered Root Cause Analysis**  
✅ **PDF Generation with Embedded Solutions (via Tabs/Spaces)**  
✅ **Cohere API + Local Model Compatible**  
✅ **Perfect for DevOps, Security Analysts, and Backend Engineers**

---

## 🛠 Tech Stack

| Component      | Tech Used                     |
|----------------|-------------------------------|
| 🌐 Frontend     | HTML, CSS, JavaScript          |
| 🧠 Backend AI   | Cohere API / Local Roberta     |
| 📁 PDF Engine   | `reportlab`, `PyPDF2`, `base64` |
| 🕵️ Steganography| Whitespace Encoding (Space/Tab) |
| 🔍 Log Matching | `SentenceTransformers`         |

---

## 📦 Project Structure

```
📁 extension/
  └── steganography-frontend.html   # Popup UI for anomaly display
📁 backend/
  └── Stegano_Basic.ipynb           # PDF Generator + Steganography
```

---

## 🧪 How It Works

1. **Log Detected** → Extension captures anomalous log entries.  
2. **AI Analysis** → Solution suggested via model (Cohere or local).  
3. **PDF Generation** → Solution embedded invisibly using whitespace.  
4. **Share** → Safe to share logs; only your decoder can extract the fix.

---

## 🧙 Magic of Steganography

We use **zero-width whitespace encoding**:  
- `' '` (space) → `0`  
- `	` (tab) → `1`  

This allows hiding entire solution messages inside a blank section of a PDF — no one can see it unless they know it's there.

---

## 🧑‍💻 Getting Started

```bash
git clone https://github.com/yourusername/log-analyzer-steganography.git
cd log-analyzer-steganography

# For backend
pip install -r requirements.txt
jupyter notebook Stegano_Basic.ipynb
```

---

## 📤 Export Sample

📝 Generated PDF looks clean — but solution is secretly hidden!

```
PDF Report:
------------
[✓] Anomaly: 503 Server Unavailable
[✓] Suggested Fix: (hidden in whitespace...)

Total Stealth Level: 🥷
```

---

## 🔒 Why This Matters

- Share logs with built-in fixes safely  
- Avoid revealing internal patch logic  
- Ideal for enterprise environments and secure workflows

---

## 🧠 Smart Matching Demo

```
Input Log: 503 Service Temporarily Unavailable
🔍 Matched Root Cause: Network failure due to outdated Nginx proxy settings
🛠 Suggested Fix: Restart proxy server and update configuration
```

---

## 🌐 Browser Extension

Easily plug into Chrome or Firefox:
- Open `steganography-frontend.html`
- Connect to backend API
- One-click PDF generation + stealth embed

---

## 👨‍💻 Author

**Himanshu Sayankar** , **Rugwed Yawalkar** , **Arya Dashputra**


---

## 📜 License

MIT License — free to use, tweak, and enhance. Steal the stealth.
