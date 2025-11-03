# ARMS Register Bot (v1.0)

An automated tool built with Python and Selenium to help students register for courses on the ARMS portal. This multi-bot dashboard allows you to monitor multiple course searches simultaneously, edit them on the fly, and get notified on success.

## Key Features

- **Multi-Bot Dashboard**: Run and monitor multiple course searches, each in its own card.
- **Smart Slot Logic**: If one bot registers a course in 'Slot A', other bots for the same user will automatically stop searching that slot.
- **Live Editing**: View a running bot, stop it, change the slots or faculty, and relaunch it without creating a new bot.
- **Headless Mode**: Run the browser invisibly in the background from the Settings menu.
- **Activity Log**: A dedicated "Log" page shows a timestamped record of every action the bots take.
- **Auto-Driver Management**: Automatically downloads the correct chromedriver.exe for your version of Chrome.

## Installation

1. Go to the Releases Page on GitHub.
2. Download the latest `ARMS.Register.Bot.vX.X.exe` file.
3. Important: If you see a "Windows protected your PC" popup, click "More info" and then "Run anyway".
4. That's it! The app will open, and a Welcome popup will guide you to a tutorial video.

## Usage (for Developers)

1. Clone the repository:
   ```
   git clone https://github.com/kalaiyarasanDev/ARMS-Register-Bot.git
   ```
2. Change to the project directory:
   ```
   cd ARMS-Register-Bot
   ```
3. (Recommended) Create a virtual environment:
   ```
   python -m venv venv
   venv\Scripts\activate
   ```
4. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```
5. Run the app:
   ```
   python app.py
   ```

## Building the .exe

1. Make sure you have all libraries from `requirements.txt` installed.
2. Install PyInstaller:
   ```
   pip install pyinstaller
   ```
3. Place your `logo.ico` file in the same folder.
4. Run the PyInstaller command:
   ```
   pyinstaller --name "ARMS Register Bot" --onefile --windowed --icon="logo.ico" app.py
   ```
5. Your final `.exe` file will be inside the `dist` folder.

## Contributing

This is an open-source project. If you find any bugs or have any issues, feel free to contact the developer. You are welcome to add modifications or new features as you see fit.

## License

This project is licensed under the [MIT License](LICENSE).

## Testing

No specific testing information is provided in the given files.

## Contact

- Developed By: Kalaiyarasan M
- Email: Cyberkalai14@gmail.com
- LinkedIn: https://www.linkedin.com/in/cyberkalai/
- GitHub: https://github.com/kalaiyarasanDev
- Instagram: https://www.instagram.com/cyber_kalai/
