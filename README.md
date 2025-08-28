# 🚀 KVM/Virt-Manager Shortcut Inhibitor 🚀

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![GitHub issues](https://img.shields.io/github/issues/LINUX-OASIS/KVM-VIRT-MANAGER-SHORTCUT-INHIBITOR-ENABLER-TOGGLE)](https://github.com/LINUX-OASIS/KVM-VIRT-MANAGER-SHORTCUT-INHIBITOR-ENABLER-TOGGLE/issues)
[![GitHub forks](https://img.shields.io/github/forks/LINUX-OASIS/KVM-VIRT-MANAGER-SHORTCUT-INHIBITOR-ENABLER-TOGGLE)](https://github.com/LINUX-OASIS/KVM-VIRT-MANAGER-SHORTCUT-INHIBITOR-ENABLER-TOGGLE/network/members)
[![GitHub stars](https://img.shields.io/github/stars/LINUX-OASIS/KVM-VIRT-MANAGER-SHORTCUT-INHIBITOR-ENABLER-TOGGLE)](https://github.com/LINUX-OASIS/KVM-VIRT-MANAGER-SHORTCUT-INHIBITOR-ENABLER-TOGGLE/stargazers)

A simple yet powerful shell script to toggle keyboard shortcut capture behavior for KVM/Virt-Manager, allowing you to seamlessly switch control between your **Host** and **Guest** operating systems.

---

## ✨ About The Project

Have you ever been working in a KVM virtual machine and tried to use a keyboard shortcut (like `Alt+Tab` or `Super+D`), only to have your host OS intercept it? This utility solves that exact problem!

By leveraging Flatpak's permission system, this script provides a simple terminal-based menu to grant or deny shortcut inhibition for `virt-manager`, `virt-viewer`, and related applications. This lets you decide on-the-fly whether your VM (Guest) or your main desktop (Host) should respond to keybindings.

### 🎯 Key Features

*   **Interactive TUI:** Easy-to-use menu powered by `whiptail`.
*   **Toggle Control:** Instantly switch shortcut priority between the Host and Guest OS.
*   **Status Check:** Quickly view the current permission status.
*   **Auto-Dependency Handling:** Automatically checks for and installs `flatpak` if it's missing.
*   **Built with Bash:** Lightweight, transparent, and easy to modify.

---

## 🖥️ Compatibility

This script is designed for Debian-based Linux distributions that use the `apt` package manager. It has been tested and is known to be compatible with:

[!Debian](https://www.debian.org/)
[!Ubuntu](https://ubuntu.com/)
[!Linux Mint](https://linuxmint.com/)

...and other Debian derivatives.

---

## 🛠️ Prerequisites & Dependencies

The script requires the following packages:

*   `flatpak`: For managing application permissions.
*   `whiptail`: For displaying the interactive menu. (`whiptail` is usually included in base installs).

> **Note**
> The script will automatically check if `flatpak` is installed. If it's not found, it will attempt to install it, add the Flathub repository, and install the GNOME software plugin for Flatpak using `sudo apt`. You will be prompted for your password.

---

## ⚙️ Installation & Usage

1.  **Clone the repository (or download the script):**
    ```sh
    git clone https://github.com/LINUX-OASIS/KVM-VIRT-MANAGER-SHORTCUT-INHIBITOR-ENABLER-TOGGLE.git
    cd KVM-VIRT-MANAGER-SHORTCUT-INHIBITOR-ENABLER-TOGGLE
    ```

2.  **Make the script executable:**
    ```sh
    chmod +x custom-KVM-INHIBIT-SHORTCUTS-ENABLE-DISABLE.sh
    ```

3.  **Run the script:**
    ```sh
    ./custom-KVM-INHIBIT-SHORTCUTS-ENABLE-DISABLE.sh
    ```

4.  **Follow the on-screen menu:**
    You will be presented with a menu to enable, disable, or check the status of shortcut inhibition.

    ```text
    ┌──────────────────────────────────────────────────────────────────────────┐
    │ KVM VIRT-MANAGER SHORTCUTS INHIBITOR ENABLE/DISABLE                      │
    ├──────────────────────────────────────────────────────────────────────────┤
    │ KVM VIRT-MANAGER SHORTCUTS INHIBITOR ENABLE/DISABLE                      │
    │                                                                          │
    │      1 [DISABLE SHORTCUT INHIBITION FOR KVM VIRT-MANAGER] {Shortcuts     │
    │      2 [ENABLE SHORTCUT INHIBITION FOR KVM VIRT-MANAGER] {Shortcuts W    │
    │      3 [STATUS]                                                          │
    │                                                                          │
    │                                                                          │
    │                                                                          │
    └──────────────────────────────────────────────────────────────────────────┘
    ```

---

## 📜 License

Distributed under the **GNU General Public License v3.0**. See `LICENSE` file for more information.

---

## 💬 Contributing

[Pull requests](https://github.com/LINUX-OASIS/KVM-VIRT-MANAGER-SHORTCUT-INHIBITOR-ENABLER-TOGGLE/pulls), [issues](https://github.com/LINUX-OASIS/KVM-VIRT-MANAGER-SHORTCUT-INHIBITOR-ENABLER-TOGGLE/issues), and suggestions are warmly welcomed! For major changes, please open an issue first to discuss what you would like to change.

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 🌐 Links

*   [**Issues**](https://github.com/LINUX-OASIS/KVM-VIRT-MANAGER-SHORTCUT-INHIBITOR-ENABLER-TOGGLE/issues)
*   [**Pull Requests**](https://github.com/LINUX-OASIS/KVM-VIRT-MANAGER-SHORTCUT-INHIBITOR-ENABLER-TOGGLE/pulls)
*   [**Releases**](https://github.com/LINUX-OASIS/KVM-VIRT-MANAGER-SHORTCUT-INHIBITOR-ENABLER-TOGGLE/releases)
*   [**Wiki**](https://github.com/LINUX-OASIS/KVM-VIRT-MANAGER-SHORTCUT-INHIBITOR-ENABLER-TOGGLE/wiki)

---

## 🧙‍♂️ Maintainer

This project is maintained by:

*   [**LINUX-OASIS**](https://github.com/LINUX-OASIS)

---
