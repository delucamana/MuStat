# MuStat for Windows and the MuStat Chrome extension: Privacy Policy

Last updated: 26 November 2026

This policy explains what MuStat for Windows (the desktop app, its tray icon and its dashboard) and the MuStat Chrome extension do with information. They work together as one product. MuStat ("we", "us") makes them. Contact: delucamana@gmail.com.

The Android app has its [own policy](privacy-policy-android).

## Summary

- MuStat keeps your listening history **on your own computer**.
- There is no account, no MuStat server, no ads, no payments and no analytics.
- **We do not receive your listening history**, unless you send it to us yourself, for example in a support email.
- The extension sends what it reads only to the MuStat app on the same computer.
- Data leaves your computer only when you sync with your own phone, export a file or share a picture.

## Information MuStat reads

### The Chrome extension

It reads what is playing in the YouTube Music and Spotify web players (music.youtube.com and open.spotify.com):

- song title, artist and album
- video ID (YouTube Music)
- playback position and song length
- whether an ad or a podcast is playing

It does not read other websites' content, cookies, passwords, account details or messages.

### The Windows app

It can read what the **Spotify desktop app** is playing through Windows media controls, the same information Windows shows in its volume pop-up: title, artist, album, track number, position and length. Other apps and browsers are not read this way.

This runs in the background while MuStat is running. You can pause tracking or quit MuStat at any time.

### History files you import

You can import your own history file from Google Takeout or Spotify's data download. MuStat reads it on your computer and saves the songs, when you played them, how long you listened and the track or video ID. Other details in those files, such as IP addresses, are not saved. MuStat does not keep a copy of the file, only its name.

## What is stored on your computer

The app's data is in `backend\app\data` inside the MuStat folder.

| Information | Why it is stored |
|---|---|
| Songs played: title, artist, album, length, date and time, seconds listened, which player, track or video ID where there is one | To show your rankings, records and search results |
| Times when tracking was paused or off | To keep your history accurate |
| Names of imported files, with the date and number of plays | So you can see and remove an import |
| Your blacklist, custom names and settings | To apply your choices |
| This computer's name, the name you enter for yourself if any, and a random device ID | To tell your own devices apart when you sync |
| For each paired phone: its name and ID, a pairing key, its last local network address and sync times | To sync with that phone again |
| Log files: technical events. While the Spotify desktop app is read, **including song titles and artists** | To find the cause of problems |
| Backups and undo copies of the history database | To recover after an app upgrade, or undo a sync or import |

Two things are stored in your browser:

- The extension keeps a short waiting list of plays, until the app confirms it received them, and a few status values.
- The dashboard remembers display preferences, such as colours and the last search choices, but not what you typed.

All of this is used only to run the features you see. We do not use it for advertising or profiling.

## When information leaves your computer

The extension sends what it reads only to the MuStat app at the local address 127.0.0.1 (port 8000). The app accepts connections only from your own computer.

Otherwise, information leaves only when you choose one of these:

| Your action | What leaves, and where it goes |
|---|---|
| **Sync with your own phone** | Your listening history, imports, blacklist, custom names, your name and device names go directly to your paired phone, over your local Wi-Fi or the phone's hotspot. |
| **Export a copy** | The same kind of information is saved to a file you choose. |
| **Save or copy a stats picture** | The picture goes to your Downloads folder or the clipboard. |
| **Open a Google Takeout or Spotify link** | Your browser opens that website. Their own privacy policies apply. |

**About sync on your network.** To find your phone, the computer sends a short message on the local network. It is **not encrypted** and contains a random device ID. The computer then connects to the phone, and the history is sent **encrypted**. The computer does not accept connections from the network. Nothing goes through the internet or through us.

MuStat makes no requests to the internet while you use it. The one exception is installation: the install script downloads the Python packages the app needs from the Python Package Index (PyPI).

## Who we share information with

**No one.** We do not sell, rent or share your information, because we do not receive it. MuStat contains no advertising, analytics or crash-reporting services from other companies.

## Chrome extension permissions

| Permission | Why |
|---|---|
| Access to music.youtube.com and open.spotify.com | To read what is playing |
| Access to the local MuStat address (127.0.0.1 / localhost, port 8000) | To send plays to the app on your computer |
| Tabs and scripting | To find open YouTube Music tabs and start tracking in them. Addresses of your other tabs are not stored or sent anywhere. |
| Storage | To keep the waiting list of plays |
| Alarms | To check the app and retry sending |

## Chrome Web Store disclosures

- **Single purpose:** to count and record the songs you play on YouTube Music and Spotify on the web, for your own listening statistics.
- **Data handled:** now-playing information from those two sites (website content and listening activity). It is sent only to the MuStat app on your computer.
- The use of information handled by the extension complies with the Chrome Web Store User Data Policy, including the Limited Use requirements.
- We do not sell or transfer this data to third parties, use it for anything unrelated to the single purpose, or use it for advertising or creditworthiness.
- No person at MuStat can read this data, because it is not sent to us.
- The extension uses no remote code.

## How your information is protected

- Your data stays on your computer, and the app listens only on the local address.
- Sync is encrypted (AES-256-GCM), and devices must first be paired with a one-time code.
- An exported file can be protected with a password. **A file saved without a password is not encrypted**, so anyone who gets it can read it.
- MuStat does **not** encrypt the data stored on your computer, including pairing keys, logs and backups. People or programs with access to your computer account may be able to read it. Use a password on your account and keep your computer protected.

No method of storing or sending data is completely secure.

## How long information is kept, and how to delete it

Your information stays on your computer until you delete it. Log files are limited in size, and older entries are replaced.

| To delete | Do this |
|---|---|
| Listening history | Settings → **Reset listening history**, for this device or all your paired devices. Undo copies are cleared too. Your settings, blacklist, custom names, paired devices, **upgrade backups and log files are kept**. |
| One import | Remove that import in Settings. |
| A paired phone | **Unpair** it in Settings. |
| Everything | Quit MuStat, delete the folder `backend\app\data`, and remove the extension in Chrome (chrome://extensions). |

**Uninstalling does not delete your data.** The uninstall script removes the shortcuts and the Windows startup entry, and leaves the data folder so your history survives a reinstall.

Files you exported, pictures you saved, and data already synced to your phone stay until you delete them there. With "this device only", the history comes back at the next sync if your phone still has it.

## If you contact us

If you email us, we receive your email address, your message and anything you attach, such as a log or screenshot. We use it only to answer you and fix the problem. We delete it within 12 months after the conversation ends, or sooner if you ask. The email is handled by our email provider (Google Gmail).

## Your rights

Privacy laws in many places, such as the EU and UK General Data Protection Regulation (GDPR), Thailand's Personal Data Protection Act (PDPA) and California law, give you rights over your personal information. These can include asking to see it, correct it, delete it, get a copy, object to or limit its use, and withdraw consent.

- **Information on your computer** is under your control. You can view it in the app, export a copy, and delete it as described above. We cannot access it.
- **Information you sent us by email:** write to delucamana@gmail.com and we will act on your request.

We do not sell personal information or share it for advertising. You may also complain to the data protection authority where you live.

## Children

MuStat is not directed at children under 13, and we do not knowingly collect information from them. If you believe a child has sent us personal information, contact us and we will delete it.

## Changes to this policy

If this policy changes, we will publish the new version on this page and update the date at the top. This version of MuStat has no ads or payments. If that changes, we will update this policy before releasing the change.

## Contact

delucamana@gmail.com
