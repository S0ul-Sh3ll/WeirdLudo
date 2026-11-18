# Weird Ludo — Privacy Policy

**Effective date:** 18 November 2026
**App:** Weird Ludo, version 1.0.8 and later ([Google Play](https://play.google.com/store/apps/details?id=com.rd.weirdludo), Android package `com.rd.weirdludo`; also available for macOS and Windows)
**Developer:** Rishabh Dahiya
**Contact:** rishabhdahiya.work@gmail.com

This policy explains what information Weird Ludo ("the app", "we") handles, why, and who it is shared with. Weird Ludo is a board game you can play against computer players on one device, with friends on the same WiFi network or hotspot, or online with other players over the internet.

## Summary

- You do **not** need an account, and the app never asks for your email, phone number, contacts or location. We do **not** sell your personal information, and we do **not** keep a database of players.
- Your player name, avatar, level and game statistics are stored **on your device**.
- When you play with friends over WiFi, your player name, avatar, level, statistics, chat messages and game moves are sent **directly to the other devices in that game on your local network**. They never reach us.
- When you **Play Online**, your device connects to our game server. It receives your player name, avatar, level, statistics, a random player ID and your game moves, and shares your name, avatar, level and statistics with the other players in your game. The server keeps this **only in memory** while you are online or your game is running, and never writes it to disk. **Online games have no typed chat**: only fixed quick lines, emoji and gifts. See [Playing online](#playing-online-internet-multiplayer).
- The Android version shows ads from **Google AdMob**. Google may collect device information, such as your advertising ID and IP address, to show and measure ads. See [Advertising](#advertising-google-admob) below.

## Information stored on your device

The app saves the following on your device so it can remember your progress:

| Data | Why |
|---|---|
| Player name and chosen avatar | Shown to you and to other players in WiFi and online games |
| Level, XP and game statistics (games played and won, captures, pieces home) | Your profile and the stats card |
| A random player ID (not linked to your identity) | Lets you rejoin a WiFi or online game after a dropped connection or closed app |
| The local network address of the last WiFi game you joined, or a note that you were playing online | The "Rejoin" button (used for up to 45 minutes, cleared when the game ends or you leave) |
| An unfinished game against the computer | The "Continue game" button |
| Your online friend list (friend codes and the names last seen) | The Friends list on the Play Online screen |
| Sound and music settings | Your preferences |

This data stays on your device. We cannot see it, except for the parts your device sends when you play online (described below). You can delete all of it at any time by clearing the app's data in your device settings or by uninstalling the app.

## Playing with friends on WiFi (local multiplayer)

When you host or join a game on the same WiFi network or hotspot, the app communicates directly between devices on that local network:

- **Finding games:** the host's device announces its room (host name, 4-digit room code, game mode, number of players) on the local network. Devices on the Join Game screen announce their player name and avatar so the host can invite them.
- **During a game:** each device shares its player name, avatar, level, statistics, random player ID, game moves, chat messages, emoji and gifts with the other devices in that game.

This information goes only to devices on your local network, not over the internet and not to us. Other players in your game can see your name, avatar, level, statistics and anything you write in chat. Chat messages are not saved after the game ends. Local network traffic is not encrypted, so please do not share personal or sensitive information in chat.

## Playing online (internet multiplayer)

**Play Online** lets you play people who are not on your network: a quick match with other players, a private room shared with a 5-digit code, or friends you add with their friend code. Online games run on a game server operated by the developer, hosted by **DigitalOcean** in a data centre in **Singapore**. The connection between your device and the server is encrypted (TLS). Traffic to the server passes through **Cloudflare**, which protects it against attacks and overload; Cloudflare handles the encrypted connection on our behalf and sees your IP address and the game traffic as it passes through, under its own [privacy policy](https://www.cloudflare.com/privacypolicy/). It does not use this data for anything else.

When you use Play Online, the server receives:

| Data | Why |
|---|---|
| Your IP address | Needed for any internet connection, so the server can send the game back to your device. It is not stored or logged by the game server |
| Player name and avatar | Shown to the other players in your game. Names are limited to 16 characters, hidden control characters are removed, and rude names are replaced with "Player" |
| Level and game statistics (games played and won, captures, pieces home) | Shown on your player card to the other players in your game |
| A random player ID (not linked to your identity) | Gives you your seat back if your connection drops or the app closes during a game |
| Your game moves, power use, and the quick lines, emoji and free gifts you send | To play the game. The server rolls the dice and checks every move, so nobody can cheat |
| Your friend list's friend codes (only while you are on the Play Online screen) | To show which of your friends are online and let you invite them. The server only answers for codes that are online right now and does not keep the list |
| The app's network version number | To tell you when the app needs an update to play online |

**No typed chat online:** in online games you can only send fixed quick lines (such as "Nice move!"), emoji and the free animated gifts. Nobody can type messages to you, so you cannot receive text from strangers.

**Friend codes:** your friend code is 6 letters and numbers made from your random player ID by a one-way calculation, so nobody can work out your player ID from it. Anyone you give your code to can add you as a friend; while you are on the Play Online screen they can see that you are online (with your player name and avatar) and invite you to their room. Your own friend list is saved only on your device. You can remove friends at any time.

**How long it is kept:** only in the server's memory while you are connected or your game is still running: a few minutes after a game ends (so your room can start a rematch), and up to 3 minutes after the last player leaves a game that has not finished. Nothing is written to disk, and the game server does not keep records of who played. We do not use this data for advertising or analytics, and we do not share it with anyone except the other players in your game. DigitalOcean provides the server hardware and network under its own [privacy policy](https://www.digitalocean.com/legal/privacy-policy) and does not receive game data from us. Cloudflare only passes the traffic through (see above) and keeps standard network logs, such as IP addresses, for a limited time for security.

## Advertising (Google AdMob)

The Android version of Weird Ludo shows banner ads provided by **Google AdMob** (Google Mobile Ads SDK). The macOS and Windows versions do not show ads.

To deliver, personalise (where permitted) and measure ads, and to prevent fraud, Google may automatically collect information from your device, including:

- the Android advertising ID and other device identifiers
- IP address and approximate location derived from it
- device and app information (such as device model, operating system version, language and app version)
- ad interactions (such as ad views and taps)
- diagnostics and crash information related to ads

This information is collected and processed by Google under Google's own policies. We do not receive it in a form that identifies you. Learn more:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [How Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites)

**Your choices:** on Android you can reset or delete your advertising ID, or opt out of ad personalisation, in your device's Settings (usually **Settings → Google → Ads** or **Settings → Privacy → Ads**). You can also limit tracking for all apps there.

## Permissions the Android app uses

| Permission | Why |
|---|---|
| Internet | To load ads, to play online, and to connect to other devices in WiFi games |
| Access network state / WiFi state | To check the connection and find your local network address for WiFi games |
| Change WiFi multicast state | To find and announce games on the local WiFi network |
| Advertising ID (`AD_ID`) | Added by the Google Mobile Ads SDK so Google can use the advertising ID for ads (see above) |
| Wake lock, foreground service, job scheduling, read basic phone state | Added by the Google Mobile Ads SDK and Android support libraries to load ads and run their short background tasks; not used by the game for anything else |

The app does **not** request access to your location, contacts, camera, microphone, photos or files.

## Sharing and selling of data

We do not sell personal information and we do not share it with anyone. The only third party that may collect information through the app is Google, for advertising, as described above. Other players only receive what is described under local multiplayer and playing online. Our hosting provider, DigitalOcean, runs the server hardware but does not receive game data from us. Cloudflare carries the online game traffic to our server, as described under playing online.

## Children

Weird Ludo is a general-audience game and is not specifically directed at children under 13. We do not knowingly collect personal information from children. If you believe a child has provided personal information through the app, contact us and we will help remove it. Online games have no typed chat, only fixed quick lines, emoji and gifts, so children cannot receive written messages from strangers; other players only see the player name, avatar, level and statistics. Because the app stores data only on the device (the online server keeps nothing after a game), clearing the app's data or uninstalling it removes everything the app saved.

## Data retention and deletion

- **On your device:** kept until you clear the app's data or uninstall the app. The rejoin information is only used for 45 minutes and is cleared when a WiFi game ends or you leave it.
- **Local multiplayer:** not stored by us. Other players' devices keep your name and stats only while the game is open.
- **Online games:** kept only in the game server's memory while you are connected or your game is running (see above), then erased. Nothing is saved to disk.
- **Advertising data:** retained by Google according to Google's Privacy Policy.

## Security

Data saved by the app is kept in the app's private storage on your device. Information exchanged in WiFi games stays on your local network. Online games use an encrypted connection (TLS) to our server, which holds game data only in memory and does not store it.

## Changes to this policy

We may update this policy when the app changes. The new version will be posted at this same address with a new effective date. Significant changes will also be noted in the app's update notes.

## Contact

Questions or requests about privacy: **rishabhdahiya.work@gmail.com**

Developer: Rishabh Dahiya
