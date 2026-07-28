# Mahmoud Presser

**A Modern Cross-Platform Auto-Clicker, Macro Sequence Builder & Auto-Typer**

![Mahmoud Presser](https://via.placeholder.com/800x400.png?text=Mahmoud+Presser)

Mahmoud Presser is a state-of-the-art, cross-platform automation tool designed for both Windows and Linux (Wayland & X11). It allows you to create highly precise macro sequences, automate clicks, and simulate typing with a beautiful modern dark-mode GUI.

## 🚀 Features
* **Cross-Platform Compatibility:** Native support for Windows and Linux (including full Wayland & X11 support).
* **Macro Sequence Builder:** Record complex multi-key combinations and mouse clicks with precise millisecond delays.
* **Smart Latin Key Resolution:** Never worry about keyboard layouts again. Keys map perfectly whether you are using QWERTY, Arabic, or shifted layouts.
* **Live Recording & Discard:** Seamlessly record macros. Pressing `ESC` cleanly stops recording without polluting your macro sequence.
* **Modern GUI:** Built with PyQt6 featuring a sleek dark palette, rounded cards, and high-contrast action badges.

---

## 🐧 Installation for Linux

### Method 1: Arch Linux (AUR) - *Recommended*
For Arch Linux users, we provide a native AUR package that is incredibly lightweight (~100 KB) because it natively pulls dependencies from the system.

1. Navigate to the `aur_package` directory.
2. Build and install the package using `makepkg`:
   ```bash
   cd aur_package
   makepkg -si
   ```
3. Once installed, simply launch **Mahmoud Presser** from your application menu or type `mahmoud-presser` in your terminal.

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

To keep the application as lightweight as possible without downloading hundreds of megabytes of bundled binaries, the Windows version runs directly via Python.

1. **Install Python:** Download and install [Python 3.10+](https://www.python.org/downloads/). *(Make sure to check "Add Python to PATH" during installation).*
2. **Install Dependencies:** Open Command Prompt and run:
   ```cmd
   pip install PyQt6 pynput
   ```
3. **Run the App:** Double click `windows_clicker.py` or run it from the command line:
   ```cmd
   python windows_clicker.py
   ```

---

## 📝 License
This project is licensed under the GPL License.
