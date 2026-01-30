```markdown
# 📺 YouTube Video Downloader

### A robust desktop GUI application for downloading YouTube videos and audio in custom formats.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-orange)
![FFmpeg](https://img.shields.io/badge/Media-FFmpeg-green)
![Status](https://img.shields.io/badge/Status-Active-success)

## 📖 Overview
**YouTube Video Downloader** is a Python-based desktop application that provides a user-friendly interface for downloading content from YouTube. Unlike basic downloaders, this tool leverages **FFmpeg** to merge high-resolution video streams with separate audio tracks, ensuring the best possible quality (up to 4K).

It features a **multi-threaded architecture** to keep the interface responsive during large downloads and includes automatic file sanitization for Windows compatibility.

---

## 📸 Application Screenshot
![App Preview](app_preview.png)

---

## ✨ Key Features
* **Format Selection:** Choose between **Audio Only (MP3)**, **Video Only**, or **Video + Audio (Merged)**.
* **Quality Control:** Select specific video resolutions (144p to 4K) or audio bitrates (128kbps - 320kbps).
* **Non-Blocking UI:** Uses Python `threading` to perform downloads in the background, preventing the app from freezing.
* **Smart Processing:** Automatically merges video and audio streams using `yt-dlp` and `FFmpeg`.
* **System Integration:** Buttons to instantly open the download folder or play the file.

---

## 🛠️ Tech Stack
* **Language:** Python 3.10+
* **GUI Framework:** Tkinter (Standard Python Interface)
* **Core Engine:** [yt-dlp](https://github.com/yt-dlp/yt-dlp) (Fork of youtube-dl)
* **Media Processing:** [FFmpeg](https://ffmpeg.org/) (Required for merging streams)

---

## 🚀 Installation & Setup

### 1. Prerequisites
This application requires **FFmpeg** to be installed and added to your system PATH.
* **Windows:** [Download FFmpeg](https://ffmpeg.org/download.html), extract it, and add the `bin` folder to your System Environment Variables.
* **Linux:** `sudo apt install ffmpeg`
* **Mac:** `brew install ffmpeg`

### 2. Clone the Repository
```bash
git clone [https://github.com/Pranav-Kukreja10/Python-YouTube-Downloader.git](https://github.com/Pranav-Kukreja10/Python-YouTube-Downloader.git)
cd Python-YouTube-Downloader

```

### 3. Install Python Dependencies

```bash
pip install yt-dlp

```

*(Note: Tkinter usually comes pre-installed with Python)*

### 4. Run the Application

```bash
python main.py

```

---

## ⚠️ Disclaimer

This tool is developed for **educational purposes only**. Please respect the copyright of content creators and YouTube's Terms of Service. Do not use this tool to download copyrighted content without permission.

---

## 👨‍💻 Author

**Pranav Kukreja**

* [GitHub Profile](https://www.google.com/search?q=https://github.com/Pranav-Kukreja10)

```


