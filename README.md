# genshin-impact-kirara
🐱 genshin-impact-kirara-helper - 原神绮良良开源辅助脚本
 
A cute, open-source helper script themed after Kirara (the cat-ear courier from Genshin Impact) – designed to simplify daily gameplay tasks without violating miHoYo's User Agreement. It’s lightweight, customizable, and packed with Kirara-style charm!
 
📝 Project Intro
 
This script is a non-cheat, non-invasive auxiliary tool built for Genshin Impact players. Inspired by Kirara’s "courier spirit," it automates repetitive daily tasks (like material tracking, commission reminders) and adds cute visual feedback (Kirara emojis, pop-ups) to make gameplay more fun.
 
⚠️ Important: This script only simulates manual mouse/keyboard operations (no memory reading or game file modification) and strictly follows miHoYo’s User Agreement. Use it at your own risk (we recommend running it with the game in windowed mode).
 
✨ Key Features (Kirara-Themed!)
 
Feature Name What It Does Cute Twist 
Courier Material Tracker Monitors your inventory of Kirara’s favorite materials (e.g., Naku Weed, Onikabuto) and alerts you when stock is low for ascension. Pops up a Kirara "package icon" 📦 when materials are missing! 
Daily Commission Reminder Sends a desktop notification if you haven’t completed 4 daily commissions by 21:00 (server time). Kirara’s voice line prompt (text-only): "Let’s finish commissions first – packages can’t wait!" 
Friendship Level Tracker Logs Kirara’s friendship level progress and calculates how many more days of companionship are needed to reach Lv.10. Shows a "happy Kirara" GIF 😊 when friendship increases! 
Screenshot Auto-Save Automatically saves screenshots of Kirara’s idle animations (triggered by pressing  F12  in-game) to a custom folder. Adds a Kirara watermark to every saved screenshot! 
Customizable Hotkeys Let you set personal hotkeys for common actions (e.g., toggle tracker, open material list). Hotkey prompts use Kirara’s color palette (pink + mint green)! 
 
🛠️ How to Install
 
1. Prerequisites
 
- Operating System: Windows 10/11 (macOS/Linux support coming soon!)
- Python Version: Python 3.9+ (download from python.org)
- Game Mode: Genshin Impact in windowed mode (1920×1080 resolution recommended)
 
2. Download the Script
 
bash
  
# Clone the repo (or download the ZIP from GitHub)
git clone https://github.com/kgwy/genshin-impact-kirara-helper.git
cd genshin-impact-kirara-helper
 
 
3. Install Dependencies
 
Run this command in the project folder to install required libraries:
 
bash
  
pip install -r requirements.txt
 
 
The  requirements.txt  includes:
 
-  pyautogui : For simulating mouse/keyboard actions
-  pillow : For processing Kirara-themed images
-  plyer : For desktop notifications
-  configparser : For loading user settings
-  psutil : For checking if Genshin Impact is running
 
🎮 How to Use
 
1. Configure the Script
Open  config.ini  in the project folder and edit these key settings:
ini
  
[Game Settings]
genshin_window_title = Genshin Impact  # Match your game window title
screenshot_folder = ./kirara_screenshots  # Where to save Kirara screenshots

[Notification Settings]
enable_kirara_voice_text = True  # Show Kirara’s text prompts
reminder_sound = True  # Play a cute "meow" sound for reminders
 
2. Launch the Script
Run the main file in the project folder:
bash
  
python kirara_helper.py
 
3. Use Hotkeys in-Game
Hotkey Function 
 F5  Toggle Material Tracker (shows/hides UI) 
 F6  Check Kirara’s Friendship Progress 
 F12  Save Kirara’s Idle Animation Screenshot 
 Esc  Exit the Script 
 
🧰 Tech Stack
 
- Core Language: Python 3.9+
- UI/Interaction: PyAutoGUI (simulate inputs), Tkinter (simple UI for settings)
- Media Processing: Pillow (image watermarks, GIF rendering)
- Notifications: Plyer (cross-platform desktop alerts)
- Configuration: ConfigParser (load/save user settings)
 
🤝 How to Contribute
 
We welcome all Kirara fans and developers to improve this script! Here’s how:
 
1. Report Bugs/Request Features
Open an Issue with:
- Bug: Describe the problem + steps to reproduce (e.g., "Material tracker doesn’t detect Onikabuto")
- Feature Request: Explain your idea (e.g., "Add Kirara’s ascension cost calculator")
2. Submit Code Contributions
1. Fork this repo → Create a feature branch ( git checkout -b feature/kirara-ascension-calc )
2. Write your code (add comments for clarity, keep Kirara’s theme!)
3. Commit changes ( git commit -m "Add Kirara ascension cost calculator" )
4. Push to your fork → Open a Pull Request (PR)
 
📜 License
 
This project is licensed under the MIT License – you can use, modify, and distribute it freely (just keep the original copyright notice and Kirara’s theme intact!). See LICENSE for details.
 
❤️ Support & Contact
 
- GitHub Repo: kgwy/genshin-impact-kirara-helper (Star us if you love Kirara!)
- Discord: Join our server Kirara’s Courier Hub to chat with other fans
- Sponsor: If you want to support development, buy us a coffee via Ko-fi – we’ll add your name to the "Kirara’s Favorite Supporters" list!
 
🐾 Final Note
 
This script is made with love for Kirara and the Genshin Impact community. Let’s keep the game fun and fair – no cheating, just cute helper tools! 🎉
"Meow~ Let’s deliver a great gameplay experience together!" – Kirara
