# 🍎🩺 Bootcamp_h34l 

A lightweight, native C# utility designed to optimize the Windows experience on Apple Bootcamp hardware. This tool provides quick toggles for common Bootcamp issues such as Bluetooth stuttering and thermal throttling, all within a minimal interface. Heal your MacBook!🩺❤️‍🩹

## ✨ Features

### 🎧 1. Ble_Fix (WiFi/Bluetooth Stutter Fix)

On many Bootcamp installations, the Windows Location Service (`lfsvc`) aggressively scans for WiFi networks, causing significant latency spikes and audio stuttering on Bluetooth headphones.

*   ✅ **Enable_Fix**: Disables and stops the Location Service to ensure smooth audio and network performance.

*   ↩️ **Disable**: Restores the service to Windows defaults.

### 💨 2. Fans_Control (Performance & Thermals)

Manages power plans to control thermal throttling and fan behavior.

*   ⚡ **HIGH PERF**: Activates the "High Performance" power plan and disables CPU idling. This forces the fans to ramp up earlier, keeping the chassis cooler during gaming or heavy workloads.

*   ⚖️ **BALANCED**: Restores the standard "Balanced" power plan with aggressive Turbo Boost enabled for everyday tasks.

*   📉 *Includes a visual temperature estimation graph.*

### 👆 3. Trackpad_Fix

Streamlines the installation of the **Mac Precision Touchpad** drivers (by imbushuo).

*   📥 Provides a direct shortcut to download the necessary drivers.

*   ✔️ Once installed, the application remembers the state and displays "Fixed_already".

## 🛠️ Usage

1.  🛡️ **Run as Administrator**: The app requires Admin privileges to modify system services (SC/Net commands) and Power Configurations (`powercfg`). And no it is not a crypto-miner lol! ⛏️😂

2.  🔽 **System Tray**: When minimized, the application retreats to the System Tray to save screen space while keeping your settings active.

3.  🖱️ **Double-Click**: Open the tray icon to restore the window.

## 🏗️ Compilation

This application is built with native C# (.NET Framework 4.7) and has **zero external dependencies** (no Python, no Node.js, no Electron 🚫).

### 📋 Requirements

*   🪟 Windows 10 or Windows 11

*   🔧 .NET Framework 4.7 (Pre-installed on most Windows systems)

### ▶️ How to Use

1.  🏃 Double-click **`Bootcamp_h34l.exe`**.

2.  🖱️ Click the options.

3.  ❤️ That's it your MacBook has been healed, he might say thanks!
