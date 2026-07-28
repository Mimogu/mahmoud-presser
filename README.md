# Mimogu Presser

**A Modern Cross-Platform Auto-Clicker, Macro Sequence Builder & Auto-Typer**

Mimogu Presser is a state-of-the-art, cross-platform automation tool designed for both Windows and Linux (Wayland & X11). It allows you to create highly precise macro sequences, automate clicks, and simulate typing with a beautiful modern dark-mode GUI.

## 🚀 Features
* **Cross-Platform Compatibility:** Native support for Windows and Linux (including full Wayland & X11 support).
* **Macro Sequence Builder:** Record complex multi-key combinations and mouse clicks with precise millisecond delays.
* **Smart Latin Key Resolution:** Never worry about keyboard layouts again. Keys map perfectly whether you are using QWERTY, Arabic, or shifted layouts.
* **Live Recording & Discard:** Seamlessly record macros. Pressing `ESC` cleanly stops recording without polluting your macro sequence.
* **Modern GUI:** Built with PyQt6 featuring a sleek dark palette, rounded cards, and high-contrast action badges.

---

## 🐧 Installation for Linux

### Method 1: Arch Linux (AUR) - *Recommended*
Mimogu Presser is officially available on the Arch User Repository (AUR). This is the absolute lightest and best way to install it, as it natively pulls the required PyQt6 dependencies.

You can install it instantly using any AUR helper (like `paru` or `yay`):
```bash
paru -S mahmoud-presser
# OR
yay -S mahmoud-presser
```
Once installed, simply launch **Mimogu Presser** from your application menu or type `mahmoud-presser` in your terminal!

### Method 2: Manual / Other Distributions
If you are on Ubuntu, Fedora, or another distribution, you can run the standalone script directly:

1. Install dependencies:
   ```bash
   sudo apt install python3-pyqt6 python3-evdev python3-gi
   pip install pynput
   ```
2. Run the script:
   ```bash
   python3 linux_clicker.py
   ```

---

## 🪟 Installation for Windows

> **⚠️ IMPORTANT REQUIREMENT FOR WINDOWS USERS:**
> To keep this application extremely lightweight (a few kilobytes instead of a 300MB+ bloated executable), this app does NOT bundle the heavy Python engine. **You MUST download and install Python and its required packages manually for the application (or its lightweight `.exe`) to work.**

### Step-by-Step Instructions:

1. **Download and Install Python:** 
   Go to [Python.org](https://www.python.org/downloads/) and install Python 3.10 or newer. 
   *(**Crucial:** When the installer opens, you MUST check the box at the bottom that says **"Add Python to PATH"** before clicking Install).*

2. **Install Required Packages:** 
   Open Command Prompt (`cmd`) and type the following command, then hit Enter:
   ```cmd
   pip install PyQt6 pynput
   ```

3. **Run the App:** 
   You can now simply double-click the `windows_clicker.py` script to run it, or if you downloaded the lightweight `.exe` version, you can now run it perfectly!

---

## 📝 License
This project is licensed under the GPL License.
