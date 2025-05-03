# 🎮 AGG - ABI's Guessing Game

**AGG** is a dynamic, multi-mode guessing game where players challenge their minds across various engaging formats — from visual puzzles to sound-based challenges.

## ✨ Features

- **Image Guess** – Identify what's shown in a picture.
- **Distorted Image Guess** – Test your perception with altered visuals.
- **Riddle Mode** – Solve brain-teasing riddles.
- **Song Mode** – Name that tune from a short audio clip.
- **Leaderboard** – Compete for the top spot!

## 🚀 Getting Started

AGG includes an installer for easy setup on Windows and Linux.
Windows:

1. **Download and run the AGG installer.**
2. Enter: AmazingWorld123
3. Launch the game from the desktop shortcut or start menu.
4. **Sign in** or **create an account**.
5. Choose your game mode and start guessing!

Linux:
1. Download the Installer:
2. Go to the GitHub release page and download the AGG.run installer.
Make the Installer Executable:
3. Open a terminal and navigate to the folder where the installer was downloaded.
4. Run the following command to make the installer executable: chmod +x AGG.run
Run the Installer:
5. Execute the installer by running: ./AGG.run
This will start the installation process.
6. Choose the Installation Directory:
The installer will ask for a directory where the game will be installed. By default, it will install to the ~/Games/AGG folder. You can change this if you want the game to be installed in a different location.
Wait for the Installation to Complete:
The installer will extract the necessary files, set permissions, and create a desktop shortcut. The process may take a few minutes.
7. Install Dependencies (if needed):
8. The installer will check for required dependencies (Python 3, Tkinter, Pillow, pygame, etc.). If any dependencies are missing, you will be prompted to install 
  them manually: sudo apt-get install python3 python3-tk python3-pip
  pip3 install Pillow pygame requests
Creating a Desktop Shortcut:
-If the installation is successful and a desktop environment is detected, a desktop shortcut (AGG.desktop) will be created in your ~/Desktop directory. You can use 
 this shortcut to easily launch the game.
Launching the Game:
9. Double-click the AGG icon on your desktop to start the game.
   Alternatively, you can run it directly from the terminal with: ~/Games/AGG/StartAGG.sh
10. **Sign in** or **create an account**.
11. Choose your game mode and start guessing!
   
> 💡 An internet connection is recommended for syncing scores to the global leaderboard.

## 🔐 Account & Progress

- Your progress is saved securely to your local system.
- High scores are synced online (when connected) to keep you ranked globally.

## 📦 System Requirements

Windows Version:

OS: Windows 10 or later
Python: Not required – comes bundled in the installer
RAM: 4 GB minimum recommended
Storage: ~150 MB free space

Linux Version:

OS: Any modern Linux distribution (e.g., Ubuntu, Fedora, Debian, Mint, etc.)
Python: Python 3.x (recommended version: 3.6 or higher)
Required Python Packages:
-Tkinter (for the GUI)
-Pillow (for image manipulation)
-pygame (for game sounds and interactions)
-requests (for HTTP requests if needed)
Permissions: Ensure that the .run file has execute permissions (chmod +x AGG.run)
RAM: 4 GB minimum recommended
Storage: ~150 MB free space
Desktop Environment: A desktop environment like GNOME, KDE, or Xfce for proper GUI functionality


## 📌 Note

AGG is currently in active development. Future updates will include new game modes, expanded media, and more.

---

© 2025 Caleb Alamu. All rights reserved.
