# bytebeat.bat-test-
# 🎵 Bytebeat Desktop Mini

Compact standalone desktop wrapper for **Dollchan Bytebeat Composer** on Windows 10/11.  
Turns the web-based algorithmic music studio into a lightweight, distraction-free mini-app.

![Preview](screenshot.png)

---

### ✨ Features
- **Zero dependencies**: Single `.bat` file (~1.5 KB). No Python, Node.js, or installers required.
- **Distraction-free compact window**: Fixed `460x580` app window with **Minimize** and **Close** buttons only (no browser tabs, bookmarks, or address bar).
- **Instant Bytebeat workspace**: Opens directly in `8000 Hz` Bytebeat mode with live oscilloscope and a classic starter formula (`t*((t>>12|t>>8)&63&t>>4)`).
- **Isolated profile**: Uses a separate temporary session (`%TEMP%\BytebeatFixedWin`), keeping your main browser history and tabs clean.

---

### 💻 Requirements
- **OS**: Windows 10 or Windows 11
- **Browser**: Pre-installed **Microsoft Edge** (built into Windows by default)
- **Internet connection**: Required to load the web engine

---

### 🚀 How to Use
1. Download `Bytebeat.bat` from the repository (or the **Releases** section).
2. Double-click `Bytebeat.bat` to launch.
3. Click the **Play (`▶`)** button inside the window to start generating 8-bit music.

> **Note on Windows SmartScreen:**  
> Since this is an unsigned `.bat` script downloaded from the internet, Windows Defender SmartScreen may show a *"Windows protected your PC"* popup on the first launch. Click **More info** → **Run anyway** to start the app.

---

### 🙏 Credits
- Powered by [Dollchan Bytebeat Composer](https://dollchan.net) created by **SthephanShi**.

---
*Made in Russia 🇷🇺*
