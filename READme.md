# Hangman's Gambit
A classic Hangman game with a modern, stylized arcade theme. Built with Python and Tkinter, featuring multiple categories, difficulty levels, sound effects, and a persistent leaderboard.

## 📸 Screenshot
Replace this with a screenshot of your game's start menu or main game screen!

## 🚀 Download & Play
The easiest way to play is to download the latest pre-built version for your operating system.

1. Go to the [Latest Release Page](https://github.com/VVeebu/Hangman-s-Gambit/releases/latest).

2. Under the **Assets** section, download the file for your system:
- `HangmansGambit-windows.zip` for Windows
- `HangmansGambit-macos.zip` for macOS
- `HangmansGambit-linux.zip` for Linux

3. Unzip the file and run the `HangmansGambit` executable.

## Key Features
- **Stylized UI:** A custom-built arcade/fantasy theme with animated elements.

- **Multiple Categories:** Choose from 8 different academic and scientific fields.

- **Variable Difficulty:** Four levels (Easy, Medium, Hard, and Expert).

- **Persistent Scoring:** A local leaderboard tracks the scores of different players.

- **Sound and Music:** Background music and sound effects for a more immersive experience.

- **Cross-Platform:** Runs as a native application on Windows, macOS, and Linux.

## 🛠️ Getting Started (For Developers)
If you want to run the game from the source code, follow these steps.

### Prerequisites
- **Python 3.13** or newer.

- **pip** (Python's package installer).

- **Git** (for cloning the repository).

### Installation
1. **Clone the repository:**
```
git clone https://github.com/VVeebu/Hangman-s-Gambit.git
cd Hangman-s-Gambit
```

2. **(Linux Only) Install System Dependencies:**
Pillow and Pygame require certain system-level libraries.

- For Debian/Ubuntu based:
```
sudo apt-get update
sudo apt-get install libjpeg-dev zlib1g-dev libfreetype6-dev libsdl2-mixer-2.0-0
```

- For Fedora based:
```
sudo dnf install freetype-devel libjpeg-turbo-devel zlib-devel SDL2-devel SDL2_mixer-devel
```

- For Arch Linux based:
```
sudo pacman -S freetype2 libjpeg-turbo zlib sdl2_mixer
```

3. **(Recommended) Create and activate a virtual environment:**

- Linux / macOS:
```
python3 -m venv venv
source venv/bin/activate
```
- Windows:
```
python -m venv venv
.\venv\Scripts\activate
```
4. **Install Python packages from `requirements.txt`:**
Make sure you have a `requirements.txt` file with this content:
```
Pillow
pygame
```
Then, run the installation command:
```
pip install -r requirements.txt
```
Usage
Once all dependencies are installed, you can run the game from the source:
```
python "Hangman's Gambit.py"
```
## License
Distributed under the MIT License.

## Acknowledgments
- Font: "Karmatic Arcade" by Vic Fieger

- Font: "Rocabe" by GGBot

- Built with Python, Tkinter, Pillow, and Pygame.

- Automated builds by GitHub Actions and PyInstaller.