<div align="center">

<img src="./assets/nyra-banner.png" alt="NYRA Discord Music Bot" width="100%">

<br>

# 🎵 NYRA

### A cute, powerful and feature-rich Discord music bot

High-quality music playback, advanced queue controls, playlists, lyrics, moderation, profiles, giveaways and much more — all inside Discord.

<br>

[![Discord](https://img.shields.io/badge/Discord-Invite%20NYRA-5865F2?style=for-the-badge\&logo=discord\&logoColor=white)](YOUR_BOT_INVITE_URL)
[![Support](https://img.shields.io/badge/Support-Join%20Server-5865F2?style=for-the-badge\&logo=discord\&logoColor=white)](YOUR_SUPPORT_SERVER_URL)
[![Status](https://img.shields.io/badge/Status-Online-success?style=for-the-badge)](YOUR_STATUS_PAGE_URL)

<br>

[Features](#-features) •
[Commands](#-commands) •
[Music Sources](#-supported-music-sources) •
[Permissions](#-required-permissions) •
[Legal](#-legal) •
[Support](#-support)

</div>

---

## 🌸 About NYRA

**NYRA** is a modern Discord bot designed to provide a smooth, simple and enjoyable music experience.

It includes high-quality music playback alongside useful server-management features such as moderation, AutoMod, invite tracking, giveaways, profiles and configurable server settings.

NYRA is designed for both small communities and large Discord servers.

---

## ✨ Features

### 🎵 Music System

* High-quality music playback
* Song and playlist searching
* Queue management
* Autoplay
* Loop track and loop queue
* Shuffle support
* Volume controls
* Music filters
* Lyrics searching
* Recently played music history
* Personal liked songs
* Configurable preferred music source
* 24/7 voice-channel mode

### 🎧 Music Controls

* Play
* Pause
* Resume
* Skip
* Stop
* Previous
* Replay
* Seek
* Volume
* Queue
* Shuffle
* Loop
* Autoplay
* Now playing

### 🛡️ Moderation and AutoMod

* Message moderation
* Spam detection
* Invite filtering
* Link filtering
* Mention-spam protection
* Emoji-spam protection
* Excessive capital-letter detection
* Warning system
* Timeout support
* Kick and ban actions
* Configurable moderation logs

### 🎉 Community Features

* Giveaways
* Invite tracking
* Invite leaderboards
* Autoroles
* User profiles
* Profile biographies
* Badges and ranks
* Server information
* User information
* Deleted-message snipe
* Custom server prefix
* Command permissions
* Command cooldowns

---

## 🌐 Supported Music Sources

NYRA may search or retrieve music information through supported providers such as:

* YouTube
* YouTube Music
* Spotify
* SoundCloud
* Apple Music
* Deezer
* Last.fm
* Lavalink-supported sources

Music-source availability may depend on NYRA's current Lavalink configuration and third-party provider availability.

---

## 🤖 Commands

NYRA supports slash commands and, where configured, prefix-based commands.

### Example Commands

```text
/play
/pause
/resume
/skip
/queue
/nowplaying
/volume
/loop
/shuffle
/autoplay
/lyrics
/liked
/history
/help
/support
```

Use NYRA's help command inside Discord to view the complete and most up-to-date command list.

---

## 🔐 Required Permissions

NYRA may request the following Discord permissions depending on the enabled features:

* View Channels
* Send Messages
* Embed Links
* Attach Files
* Read Message History
* Add Reactions
* Connect
* Speak
* Use Voice Activity
* Manage Messages
* Manage Roles
* Moderate Members
* Kick Members
* Ban Members
* Manage Channels
* Manage Server

Only grant NYRA the permissions required by the features you plan to use.

NYRA should never be given the `Administrator` permission unless it is strictly necessary and you fully understand the security implications.

---

## 🛰️ Gateway Intents

NYRA currently uses the following privileged Discord Gateway Intents:

### Server Members Intent

Used for:

* Member join and leave events
* Autoroles
* Invite tracking
* Moderation
* Member-related commands
* Role management

### Message Content Intent

Used for:

* Prefix commands
* AutoMod processing
* Spam and link detection
* Deleted-message snipe
* Message-based command handling

### Presence Intent

Used for:

* User status
* Device information
* Discord activities
* Presence-related profile commands

Presence Intent is optional for NYRA's core music functionality and may be disabled if presence-related features are removed.

---

## 🔒 Privacy and Data

NYRA may process Discord IDs, server configuration, command information, music searches, liked songs, profiles, invite statistics, giveaway participants and moderation information as required to provide its features.

NYRA does not sell user information.

For full details, read the following documents:

* [Privacy Policy](./PRIVACY.md)
* [Terms of Service](./TERMS.md)
* [Security Policy](./SECURITY.md)

---

## ⚠️ Third-Party Services

NYRA depends on third-party platforms and services including Discord, Lavalink and supported music or lyrics providers.

Availability and functionality may be affected by:

* Discord API changes
* Lavalink outages
* Music-provider restrictions
* Rate limits
* Network interruptions
* Provider policy changes

NYRA does not own or host music, lyrics, artwork or third-party media content.

---

## 🛡️ Security

Never publicly share:

* Discord bot tokens
* Spotify client secrets
* Lavalink passwords
* Database files
* API keys
* Environment files
* Private configuration files

All production credentials should be stored using environment variables.

Example:

```env
DISCORD_TOKEN=your_discord_bot_token
SPOTIFY_CLIENT_ID=your_spotify_client_id
SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
LAVALINK_HOST=your_lavalink_host
LAVALINK_PORT=2333
LAVALINK_PASSWORD=your_lavalink_password
```

The `.env` file must be included in `.gitignore`.

```gitignore
.env
.env.*
node_modules/
database/
*.sqlite
*.sqlite3
*.db
logs/
backups/
src/config.json
```

Security vulnerabilities should be reported privately through the official NYRA Support Server.

Do not publish security vulnerabilities in public GitHub issues.

---

## 📄 Legal

By inviting or using NYRA, users and server administrators agree to:

* [NYRA Privacy Policy](./PRIVACY.md)
* [NYRA Terms of Service](./TERMS.md)

Server administrators are responsible for configuring NYRA appropriately and informing their community about enabled moderation, logging, invite-tracking and deleted-message features.

---

## 💬 Support

Need help with NYRA?

* Join the official support server: [NYRA Support](YOUR_SUPPORT_SERVER_URL)
* Invite NYRA: [Add NYRA to Discord](YOUR_BOT_INVITE_URL)
* Report bugs through the support server
* Submit feature suggestions through the appropriate suggestion channel

When reporting an issue, include:

* The command used
* The error message
* Your Discord server ID
* Relevant screenshots
* Steps to reproduce the problem

Never include your Discord token, API keys or passwords.

---

## 📊 Bot Information

| Information     | Details                         |
| --------------- | ------------------------------- |
| Bot Name        | NYRA                            |
| Platform        | Discord                         |
| Primary Purpose | Music and community management  |
| Commands        | Slash and prefix commands       |
| Music Engine    | Lavalink                        |
| Database        | SQLite                          |
| Language        | Node.js / JavaScript            |
| Support         | Official Discord Support Server |

---

## 🌟 Support NYRA

You can support NYRA by:

* Adding NYRA to your Discord server
* Sharing NYRA with other communities
* Reporting bugs
* Suggesting useful features
* Providing constructive feedback
* Supporting the official Discord community

---

<div align="center">

### Made with 🎵 for Discord communities

**NYRA © 2026**

[Invite Bot](YOUR_BOT_INVITE_URL) •
[Support Server](YOUR_SUPPORT_SERVER_URL) •
[Privacy Policy](./PRIVACY.md) •
[Terms of Service](./TERMS.md)

</div>
