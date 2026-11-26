# MuStat for Windows and the MuStat Chrome extension: Privacy Policy

Last updated: 26 November 2026

This policy covers MuStat for Windows (the desktop app, its tray icon and its dashboard) and the MuStat Chrome extension, which work together as one product. The Android app has its own policy. MuStat is made by MuStat ("we", "us"). Contact: delucamana@gmail.com.

## The short version
MuStat keeps your listening history on your own computer. It has no account, no server, no ads and no analytics. The extension and the app talk only to each other, on your computer. We never receive your data.

## What MuStat reads
**The Chrome extension** reads what is playing in the YouTube Music and Spotify web players (music.youtube.com and open.spotify.com): song title, artist, album, the video ID (YouTube Music), how far into the song you are, the song's length, and whether the player is showing an ad or a podcast. Ads and podcasts are ignored. The extension reads no other websites' content, no cookies, no passwords, no account or profile details, and no messages. Its "tabs" permission is used only to find YouTube Music tabs; the addresses of your other tabs are not stored or sent anywhere.

**MuStat for Windows** can also read what the Spotify desktop app is playing, through Windows' media controls (the same information Windows shows in its volume pop-up): title, artist, album, track number, position and length. It looks only at Spotify. Other apps and browsers are not read through this feature.

You can also import a history file you downloaded yourself (Google Takeout or Spotify's data download). The file is read on your computer only.

## Where the information goes
- The extension sends what it reads only to the MuStat app on the same computer, at the local address 127.0.0.1 (port 8000). The app listens only on that local address, not on your network.
- Until the app confirms receipt, the extension keeps a short waiting list in the browser's own extension storage.
- MuStat makes no requests to the internet. The one exception is installation: the install script downloads the app's required Python packages from the public Python Package Index (PyPI).
- Links in the app (for example to Google Takeout or Spotify's data page) open in your browser. Those sites have their own policies.

## What is stored on your computer
Everything is kept in the app's data folder (`backend\app\data` inside the MuStat folder):
- **Your history database:** plays, listening time, song lengths, the files you imported, your blacklist and custom list, the times tracking was paused, and your sync settings. If you set a name for yourself, it is stored here too, along with this computer's name.
- **Settings:** appearance and run mode.
- **Logs:** technical logs. When the Spotify desktop app is being read, the log also records the title and artist of songs as they start and when a play is counted. Logs are kept in small rotating files.
- **Backups and undo copies:** before some app upgrades, MuStat makes a full copy of your database and keeps it until you delete it. Syncing and importing a MuStat copy also keep undo copies, which are replaced at the next sync and cleared by Reset.
- **Sync pairing keys:** if you pair a phone, the long-term key for that pair is stored in the database.
- The dashboard remembers a few display preferences (like colours and the last search choices) in your browser's local storage, for the local address 127.0.0.1:8000. It does not remember what you typed in search.

## When data leaves the app
Only when you choose to:
- **Sync with your own phone** over your local Wi-Fi or the phone's hotspot, after pairing with a one-time code. The connection is encrypted. Your computer never accepts connections from the network: it sends a short "MuStat phone here?" message on the local network (not encrypted, containing only a random device ID) and then connects to the phone itself. Nothing goes through the internet or through us.
- **Export a copy** to a file you choose. It can be password-protected (the box is ticked by default). A file saved without a password is not encrypted.
- **Save or copy a stats picture.** The picture is drawn on your computer and saved to your Downloads folder or copied to the clipboard.

## What we do not collect
No name, email, account, location, contacts, advertising ID, browsing history or usage analytics. We do not sell or share data, because we do not have it.

## Deleting your data
- **Reset listening history** (Settings → Your data): erases plays, listening time, imports and song lengths, either on this device only or on all your paired devices. Your settings, blacklist, custom list and paired-device records are kept.
- **Remove an import** removes only what that import added.
- **Reset does not delete** the automatic backups, undo copies of other kinds, or the log files. To remove everything, quit MuStat and delete the data folder (`backend\app\data`), and remove the extension in Chrome (chrome://extensions), which clears its storage.
- The uninstall script removes the shortcuts and the Windows startup entry. It leaves your data folder in place, so your history survives a reinstall.
- Copies you exported, pictures you saved, and phones you paired keep their own data until you delete it there.

## Chrome extension: Chrome Web Store disclosures
- **Single purpose:** count and record the songs you play on YouTube Music and Spotify on the web, for your own listening statistics.
- **Data the extension handles:** now-playing information from those two sites (website content and listening activity). It is sent only to the MuStat app on your computer.
- We do not sell or transfer this data to third parties, we do not use it for anything unrelated to the extension's purpose, and we do not use it for advertising or creditworthiness.
- The extension uses no remote code.

## Children
MuStat is not directed at children under 13 and collects no data from anyone.

## Changes
If this policy changes we will update the date above and tell users in the app or on the download page for meaningful changes.

## Contact
delucamana@gmail.com
