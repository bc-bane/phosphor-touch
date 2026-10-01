# Phosphor Touch Releases

Official host desktop companion app for **Phosphor** — turning your iPad or Android tablet into an ultra-low latency monitor and interactive touch display.

[![Releases](https://img.shields.io/github/v/release/bc-bane/phosphor-touch?color=brightgreen&label=Latest%20Release)](https://github.com/bc-bane/phosphor-touch/releases/latest)
[![Platforms](https://img.shields.io/badge/Platforms-macOS%20%7C%20Windows-blue)](https://github.com/bc-bane/phosphor-touch/releases)

---

## 🚀 Overview

**Phosphor Touch** is a lightweight menu bar / system tray utility that runs silently on your computer. When connected to the **Phosphor** tablet app over local Wi-Fi, it seamlessly translates touch gestures, taps, trackpad navigation, and keyboard input into native operating system events.

* ⚡ **Ultra-Low Latency** (~2ms local WebSocket event stream)
* 📡 **Zero-Config Discovery** (Automatic Bonjour / mDNS pairing)
* 🖥️ **Multi-Display & Resolution Aware** (Dynamic geometry synchronization)
* 🪟 **macOS & Windows Support**

---

## 📥 Downloads & Installation

Get the latest release for your operating system from the **[Releases Page](https://github.com/bc-bane/phosphor-touch/releases/latest)**.

| Platform | Download Asset | Notes |
| :--- | :--- | :--- |
| **macOS** | `.dmg` or `.zip` (Universal) | Apple Silicon & Intel support. Requires Accessibility permission. |
| **Windows** | `.exe` (Installer or Portable) | Windows 10/11 (x64) |

---

## ⚙️ Platform Setup & Permissions

### macOS
1. Open the downloaded `.dmg` and drag **Phosphor Touch** to your **Applications** folder.
2. Launch the app. It will appear as an icon in your macOS menu bar.
3. Grant **Accessibility** permissions when prompted:
   * Go to **System Settings → Privacy & Security → Accessibility**.
   * Toggle **Phosphor Touch** on.

### Windows
1. Download and run the `.exe` installer or standalone portable executable.
2. The app will launch into your system tray (notification area).
3. If Windows SmartScreen displays a warning on first run, click **More info** → **Run anyway**.

---

## 📱 How It Works

1. Launch **Phosphor Touch** on your computer.
2. Ensure your tablet and computer are connected to the same local Wi-Fi network.
3. Open the **Phosphor** app on your iPad or Android device — it will automatically discover your host and connect.
4. Interact with your computer using touch, pencil/stylus, or on-screen gestures!

---

## 🔗 Related Repositories

* **Phosphor Desktop (Source Code)**: [github.com/bc-bane/phosphor_desktop](https://github.com/bc-bane/phosphor_desktop)
