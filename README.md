# MusicBot

MusicBot is a feature-rich Discord music bot that streams high-quality audio from various sources including YouTube and Spotify.

## Features

- 🎵 **High-Quality Music Playback**: Stream music from YouTube, Spotify, and more.
- 🎚 **Advanced Audio Controls**: Volume control, bass boost, and equalizer.
- 📃 **Playlist Management**: Create, save, and load custom playlists.
- ⏯ **Seamless Playback**: Play, pause, skip, and queue management.
- 🔍 **Search Functionality**: Search and play songs directly from Discord.
- 🔄 **Auto-Play**: Continuous playback based on your song preferences.
- 🔒 **Permissions**: Role-based access control for bot commands.

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/) v14 or higher
- [Discord.js](https://discord.js.org/) v13 or higher
- [FFmpeg](https://ffmpeg.org/download.html) (for audio processing)

### Clone the Repository

```bash
git clone https://github.com/soorajtech/music-bot.git
```
``` bash
cd music-bot
```

### Install Dependencies
```bash
npm install
```
### Configuration
- Create a .env file in the root directory of the project.
- Add the following variables to the .env file:
```bash
DISCORD_TOKEN=your_discord_bot_token
SPOTIFY_CLIENT_ID=your_spotify_client_id
SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
```
### Run the Bot
```bash
npm start
```

## Usage
Invite the bot to your Discord server using the provided invite link. Use the following commands to interact with the bot:

- !play <song_name_or_url>: Play a song.
- !pause: Pause the current song.
- !resume: Resume the paused song.
- !skip: Skip to the next song.
- !queue: View the current song queue.
- !volume <value>: Set the volume (1-100).
- !playlist <action> <playlist_name>: Manage playlists (create, add, remove, load).
- !search <query>: Search for a song.

### Fork the repository.
- Create a new branch: git checkout -b my-feature-branch.
- Make your changes and commit them: git commit -m 'Add some feature'.
- Push to the branch: git push origin my-feature-branch.
- Create a new Pull Request.

### Contact
For any questions or suggestions, feel free to reach out to us:

- Email: soorajskumar004@gmail.com
- Discord: soorajsk
Thank you for using MusicBot! Enjoy your music experience! 🎶
