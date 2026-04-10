# ScreenCraft v2.0.0

**A Modern, Feature-Rich Screenshot & Screen Recording Tool for Linux**

![Platform](https://img.shields.io/badge/Platform-Linux%20Mint%20%7C%20Ubuntu-E95420?style=flat-square&logo=linux&logoColor=white)
![Language](https://img.shields.io/badge/Language-Python%203-3776AB?style=flat-square&logo=python&logoColor=white)
![UI](https://img.shields.io/badge/UI-GTK3-7DF111?style=flat-square&logo=gnome)

---

## 🌟 Features

ScreenCraft is built to be a reliable, beautiful, and robust daily driver for capturing your screen on Linux desktops.

- **Auto-Scrolling Screenshots:** Capture entire long web pages or documents seamlessly. Includes a Live Progress HUD to track scrolling captures in real-time.
- **Post-Capture Actions:** Instantly after taking a screenshot, a toast notification appears allowing you to Copy to Clipboard, Edit Image, or Open Folder.
- **Screen Recording:** Record full screen, specific windows, or drawn regions. Supports capturing System Audio and Microphone input simultaneously via FFmpeg.
- **Visual History Manager:** Browse your past captures and recordings directly inside the app with thumbnail previews.
- **Robust Bootloader:** Smart detection of your DISPLAY environment and resilient file path fallback mechanisms to prevent crashes.
- **Material Design 3:** A premium dark-mode interface with smooth animations and intuitive controls.

---

## 🚀 Quick Install

The easiest way to get started is using the automated install script. This will install necessary system dependencies and add ScreenCraft to your application menu.

### 1. Clone the Repository

```bash
git clone https://github.com/RabinAlam/ScreenCraft.git
cd ScreenCraft
```

### 2. Run the Installer

```bash
bash quick_install.sh
```

*(This script installs `scrot`, `xdotool`, `ffmpeg`, `wmctrl`, `xclip`, and python GTK dependencies. It handles folder permissions gracefully).*

---

## 💻 Manual Launch

If you prefer not to install the desktop shortcuts, you can launch the app directly from its folder using the optimized launch script:

```bash
cd /path/to/ScreenCraft
bash run.sh
```

> **Note:** Always use `run.sh` to start the app natively, as it ensures your X11 Display environment is correctly mapped to prevent startup crashes.

---

## 🛠 Dependencies

If you are installing manually, ensure you have the following packages installed:

```bash
sudo apt install scrot xdotool ffmpeg wmctrl x11-utils xclip libnotify-bin python3-gi python3-gi-cairo gir1.2-gtk-3.0 python3-pil
```

---

## ⚙️ Configuration

ScreenCraft includes a built-in **Settings** tab where you can:
- Set custom save directories for Screenshots and Recordings.
- Toggle desktop notifications on/off.
- Run the built-in **Dependency Checker** to instantly see if any core system tools are missing.

---

## 🤝 Contributing & License

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/RabinAlam/ScreenCraft/issues).

**License:** This project is open-source. Do whatever you'd like with it!
