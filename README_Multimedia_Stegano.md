
# 🎓 Capstone Project: Multimedia Steganography System

> 🧠 A complete suite for hiding and extracting information in Images, Audio, Video, and PDF files  
> 🕵️‍♂️ Combines classical steganography with modern techniques in an interactive, user-friendly interface  
> 👨‍💻 Developed as an academic final-year capstone project

---

## 🧩 Project Overview

This project explores the field of **Multimedia Steganography**, which is the art of hiding information in plain sight — inside digital media like images, videos, audio, and documents — such that only the intended recipient can detect and extract it.

Implemented using Python and web technologies, this system provides a full pipeline to:
- 📥 **Encode** secret messages or files into media
- 📤 **Decode** hidden content from stego-media
- 🖼️ Visualize or listen to the results
- 🌐 Use via a browser-based frontend or notebook backend

---

## 🎯 Steganography Techniques Implemented

### 🖼️ Image Steganography
- Embeds secret messages or images into cover images using **Least Significant Bit (LSB)** encoding
- Supports color images (RGB) for larger embedding capacity

### 🔊 Audio Steganography
- Hides secret messages within audio files (e.g., `.wav`)
- Leverages LSB embedding in sound wave samples

### 🎥 Video Steganography
- Extracts frames from a video
- Applies image steganography frame-by-frame
- Reconstructs video from modified frames

### 📄 PDF Steganography (Whitespace)
- Hides binary messages using:
  - `' '` (space) → `0`
  - `\t` (tab) → `1`
- Stealth encoding invisible to the reader

---

## 🌐 Frontend UI

The included `steganography-frontend.html` provides a simple yet powerful interface:
- Select media type (Image, Audio, Video, PDF)
- Input the secret message
- Choose cover media and output location
- Trigger encoding or decoding

> ✅ No advanced tools required — just open in a browser and use the system locally

---

## 📁 File Structure

```
📄 Stegano_Basic.ipynb
    - Main notebook implementing encoding/decoding for all media types

🌐 steganography-frontend.html
    - Web-based frontend interface for running the process interactively
```

---

## 🔧 Tech Stack

| Component     | Tech Used                |
|---------------|--------------------------|
| Core Language | Python                   |
| UI            | HTML, JavaScript         |
| Image         | OpenCV, NumPy, PIL       |
| Audio         | Wave, NumPy              |
| Video         | OpenCV                   |
| PDF           | ReportLab, PyPDF2        |
| Notebook      | Jupyter (for demos/test) |

---

## ▶️ How to Use

### Option 1: Use via Notebook

1. Open `Stegano_Basic.ipynb` in Jupyter
2. Run the cells under desired media type (image/audio/video/pdf)
3. Encode your message, save the stego-media
4. Use decode cells to retrieve message

### Option 2: Use via Frontend

1. Open `steganography-frontend.html` in a browser
2. Select file and message
3. Click "Encode" or "Decode"
4. Save or extract results

---

## 🎓 Educational Value

This capstone project provides hands-on exposure to:
- Data encoding/decoding theory
- Digital media manipulation
- Practical cryptography principles
- Python multimedia libraries
- Secure communication techniques

---

## 👨‍🎓 Developed By

**Himanshu Cha**  
🎓 B.Tech Final Year | Capstone Project | Multimedia Security

---


## 🏁 Final Note

> Whether you're sharing a secret through a song or an image, this system ensures it's **hidden in plain sight**. Perfect for educational demos, research, or entry-level secure communication systems.
