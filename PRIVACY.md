# NYRA Privacy Policy

**Effective Date: August 3, 2026**

This Privacy Policy explains how NYRA (“NYRA,” “the Bot,” “we,” “us,” or “our”) collects, uses, stores, and shares information when you interact with NYRA through Discord.

By adding or using NYRA, you acknowledge the practices described in this Privacy Policy.

## 1. Information We Collect

### 1.1 Discord Information

Depending on the features used, NYRA may process:

* Discord user IDs
* Discord server, channel, role, message, and voice-channel IDs
* Usernames, display names, avatars, account creation dates, and other publicly available Discord profile information
* Server names, icons, member counts, and server-owner information
* Member join and leave events
* User presence, status, device type, and activity information where the Presence Intent is enabled
* Permissions and roles required to perform moderation and utility commands

### 1.2 Commands and Message Content

NYRA supports prefix-based commands and may therefore process the content of messages sent in servers where the Bot is installed.

Message content may be processed for:

* Recognizing and executing prefix commands
* Detecting spam, links, invites, excessive mentions, capital letters, emoji spam, or other configured AutoMod violations
* Displaying the most recently deleted message through the snipe feature
* Logging command usage where operational logging has been enabled
* Enforcing command permissions, cooldowns, blacklists, and ignored channels

NYRA does not ordinarily store every server message in its persistent database.

When the snipe feature is active, the latest deleted message’s content, author, attachment URL, and deletion time may temporarily remain in the Bot’s memory until it is replaced by another deleted message or the Bot restarts.

AutoMod may temporarily retain recent message content in memory to detect repeated spam. AutoMod violation details may also be posted to a moderation-log channel selected by the server administrators.

### 1.3 Music Information

NYRA may process or store:

* Music search queries
* Song titles, artists, URLs, thumbnails, source names, identifiers, and durations
* The requesting user’s Discord information
* A server’s recently played music history
* Songs saved by individual users as liked or favorite songs
* Music-source preferences
* Queue, playback, loop, volume, autoplay, and 24/7 configuration

NYRA currently stores up to 20 recently played tracks for each server. Liked songs remain associated with the user’s Discord ID until they are removed or deletion is requested.

### 1.4 Profiles and Preferences

When profile features are used, NYRA may store:

* A user-provided profile biography
* Badges and ranks
* Friend or relationship-related profile fields
* Allowed or denied command settings
* No-prefix access
* Blacklist status and reason
* Preferred music source

Users should not submit passwords, payment information, private addresses, health information, or other sensitive personal information through profile biographies or Bot commands.

### 1.5 Invite Tracking and Member Management

When enabled by server administrators, NYRA may store:

* Joining member ID
* Inviter ID
* Invite code
* Join and leave timestamps
* Invite totals
* Whether an account was classified as new, fake, or rejoining
* Autorole and invite-tracking configuration

Invite information is used only to provide invite tracking, rankings, and server-management functionality.

### 1.6 Giveaways

For giveaways, NYRA may store:

* Giveaway message, server, and channel IDs
* Host ID
* Prize description
* Participant user IDs
* Winner count
* Start and end information

Ended giveaway records are normally removed from the Bot’s local database after approximately 24 hours.

## 2. How We Use Information

We use collected information to:

* Operate music playback and music-discovery features
* Execute commands and interactions
* Maintain liked songs and music history
* Provide profiles and user preferences
* Provide moderation, AutoMod, invite tracking, giveaways, and autoroles
* Diagnose technical errors and prevent abuse
* Enforce blacklists, cooldowns, permissions, and security restrictions
* Maintain the Bot’s stability and improve its functionality
* Respond to support, privacy, and deletion requests

We do not sell personal information.

## 3. Third-Party Services

NYRA relies on Discord and may use third-party services to provide music, metadata, recommendations, lyrics, and media playback.

Depending on the command used, music titles, artist names, URLs, or search queries may be transmitted to services such as:

* Discord
* The configured Lavalink server
* Spotify
* Last.fm
* YouTube or YouTube Music
* SoundCloud
* Apple Music
* Deezer
* LRCLIB
* Lyrics Finder
* Other configured music or lyrics providers

These services process information under their own privacy policies and terms. NYRA does not control the independent data practices or availability of third-party services.

## 4. Data Storage and Retention

NYRA primarily stores persistent information in a local SQLite database operated by the Bot owner.

Retention depends on the type of information:

* Server configuration is retained while needed to operate enabled features.
* Some server configuration and invite-log data is deleted when NYRA is removed from a server.
* Recently played music history may remain until it is manually cleared or deletion is requested.
* Liked songs and user profiles remain until removed or deletion is requested.
* Giveaway records are generally removed approximately 24 hours after the giveaway ends.
* Temporary spam-detection data is held in memory for a limited period.
* Deleted-message snipe data remains in memory until replaced or the Bot restarts.
* Operational or moderation messages posted to Discord channels remain according to the server’s Discord settings and administrator actions.

NYRA may retain limited information for longer where reasonably necessary to prevent abuse, resolve disputes, enforce these Terms, or comply with legal obligations.

## 5. Data Sharing

Information may be shared only:

* With Discord as required to operate the Bot
* With music, lyrics, recommendation, or hosting providers necessary to complete a requested feature
* With server administrators through moderation, command, invite, or AutoMod logs
* With authorized NYRA operators for security, maintenance, backup, and support
* Where legally required or necessary to protect users, NYRA, or third parties

We do not authorize third parties to use NYRA data for independent advertising.

## 6. Data Security

We use reasonable administrative and technical measures intended to protect stored information.

However, no online service, database, Discord integration, or transmission method can be guaranteed to be completely secure. Users should avoid submitting sensitive or confidential information through NYRA.

## 7. User and Server-Administrator Choices

Users and server administrators may:

* Remove liked songs using the available commands
* Clear or replace profile-biography information
* Disable AutoMod, invite tracking, or other configurable features
* Remove NYRA from a server
* Request access to or deletion of information associated with a Discord user or server ID

A deletion request must include the relevant Discord user ID or server ID so that the records can be located.

Requests may be submitted through the official NYRA Support Server linked by the Bot’s support command.

Some moderation records posted directly inside Discord channels must be removed by the server’s administrators.

## 8. Children and Minimum Age

NYRA is intended only for people who meet Discord’s minimum-age requirements in their country.

We do not knowingly design NYRA to collect information from users who are not permitted to use Discord. A parent, guardian, or affected user may contact us if they believe prohibited information has been collected.

## 9. International Processing

NYRA’s infrastructure and third-party providers may process information in countries other than the user’s own country. Data-protection standards may differ between jurisdictions.

## 10. Changes to This Policy

We may update this Privacy Policy when NYRA’s functionality, infrastructure, data practices, or legal requirements change.

The effective date at the top of this policy will be updated when material changes are made. Continued use of NYRA after an update constitutes acknowledgement of the revised policy.

## 11. Contact

For privacy questions, data-access requests, or deletion requests, contact the NYRA team through the official Support Server linked in NYRA’s `/support` or support command.
