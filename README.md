# Midnight-Player
Midnight Player is a modern python audio player. It provides functionalities like playlist management, playback speed adjustment, and a dark/light theme.

## Features
- Audio Playback: Supports various audio formats including MP3, WAV, FLAC, OGG, M4A, AAC, and WMA.
- Playlist Management: Create and manage playlists with ease.
- Playback Speed Control: Adjust playback speed between 0.5x and 2x.
- Dark and Light Themes: Choose between dark and light themes for an optimal UI experience.
- Cross-Platform: Available for Windows, Ubuntu (DEB) Linux distributions.

## Installation

### Windows Installer (EXE)

1. Download the installer from the Releases section.
2. Run the installer and follow the on-screen instructions.

### Ubuntu (DEB)

1. Download the `.deb` package from the Releases section.
2. Install it using the following commands:
    ```bash
    sudo dpkg -i midnight-player_1.0-1_amd64.deb 
    sudo apt-get install -f
    ```
### From Source

1. Ensure you have Python 3.7+ and pip installed.
2. Clone the repository:
    ```bash
    git clone https://github.com/varckin/Midnight-Player
    cd Midnight-Player
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the application:
    ```bash
    python main.py
    ```

## Usage

- Launch the application.
- Use the `File` menu to open audio files or folders.
- Create and manage playlists via the `Add Playlist` and `Remove Playlist` options.
- Control playback speed using the dropdown menu.
- Adjust the volume and navigate through tracks using the sliders.
