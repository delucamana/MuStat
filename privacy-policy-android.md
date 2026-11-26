# MuStat for Android: Privacy Policy

Last updated: 26 November 2026

This policy explains what the MuStat app for Android (app ID com.mustat.jj) does with information. MuStat ("we", "us") makes the app. Contact: delucamana@gmail.com.

MuStat for Windows, including its Chrome extension, has its [own policy](privacy-policy-windows).

## Summary

- MuStat keeps your listening history **on your phone**.
- There is no account, no MuStat server, no ads, no payments and no analytics.
- **We do not receive your listening history**, unless you send it to us yourself, for example in a support email.
- Data leaves your phone only when you sync with your own devices, export a file, share a picture or share the troubleshooting log.
- The app does not read your notifications or messages.

## Information the app reads

### What your music apps are playing

To count your listening, MuStat asks for Android's **Notification access**. Android requires this for an app to see other apps' media players. MuStat uses it only for the players of **YouTube Music** and **Spotify**, and reads:

- song title, artist and album
- song length and playback position
- whether it is playing or paused, and which controls the player offers (used to recognise ads and podcasts)

Notification access could technically let an app read notifications. **MuStat does not read the content of any notification**, including messages.

This happens in the background, after you allow it. You choose when MuStat tracks:

- **Only while the app is open** (the default): it keeps tracking in the background until you swipe MuStat away from Recent apps or restart the phone.
- **Always, in the background:** it also tracks when MuStat is not open, including after a restart.

You can pause tracking, switch off a music app in MuStat's Settings, or turn Notification access off in Android settings at any time.

### History files you import

You can import your own history file from Google Takeout (YouTube Music) or from Spotify's data download. MuStat reads it on your phone and saves the songs, when you played them, how long you listened and the track or video ID. Other details in those files, such as IP addresses, are not saved. MuStat does not keep a copy of the file, only its name.

## What is stored on your phone

| Information | Why it is stored |
|---|---|
| Songs played: title, artist, album, length, date and time, seconds listened, which music app, track or video ID where there is one | To show your rankings, records and search results |
| Times when tracking was paused or off | To keep your history accurate |
| Names of imported files, with the date and number of plays | So you can see and remove an import |
| Your blacklist, custom names and settings | To apply your choices |
| This device's name (taken from your phone's name or model; you can change it), the name you enter for yourself if any, and a random device ID | To tell your own devices apart when you sync |
| For each paired device: its name and ID, a pairing key, its last local network address and sync times | To sync with that device again |
| A troubleshooting log: recent tracking events, **including song titles and artists**, and ads that were skipped | To find out why something was or was not counted |

All of this is used only to run the features you see in the app. We do not use it for advertising or profiling.

## When information leaves your phone

Only when you choose one of these:

| Your action | What leaves, and where it goes |
|---|---|
| **Sync with your own devices** | Your listening history, imports, blacklist, custom names, your name and device names go directly to the devices you paired, over your local Wi-Fi or hotspot. |
| **Export a copy** | The same kind of information is saved to a file in the place you choose. |
| **Share or save a picture** | A picture of your stats goes to the app you pick, or to your Photos. |
| **Share the troubleshooting log** | The log and your Android version go to the app you pick. |
| **Open a Google Takeout or Spotify link** | Your browser opens that website. Their own privacy policies apply. |

**About sync on your network.** While MuStat is open, devices find each other with short messages on the local network. These messages are **not encrypted**. They contain a random device ID and a few technical details needed to connect, **not your name or your device's name**. Your phone replies only when a message carries the ID of a paired device, or, while you are pairing, to a device looking for one to pair with. The history itself is sent **encrypted**. Nothing goes through the internet or through us.

The app makes no requests to the internet. Android's "Internet" permission is needed for the local network connection used by sync.

## Who we share information with

**No one.** We do not sell, rent or share your information, because we do not receive it. The app contains no advertising, analytics or crash-reporting code from other companies.

**Google Play.** If you install the app from Google Play, Google handles information under [Google's privacy policy](https://policies.google.com/privacy). Google may show us statistics such as install numbers and crash reports. These do not include your listening history.

## Permissions the app asks for

| Permission | Why |
|---|---|
| Notification access | To see what YouTube Music and Spotify are playing |
| Show notifications (optional) | To tell you if the phone stopped MuStat and a song was not counted |
| Internet, network state and Wi-Fi multicast | To find and sync with your own devices on the local network |

## How your information is protected

- Your history is kept in the app's private storage, which Android keeps apart from other apps.
- Android backup is switched off for MuStat, so the app's data is not backed up to your Google account.
- Sync between your devices is encrypted (AES-256-GCM), and devices must first be paired with a one-time code.
- An exported file can be protected with a password. **A file saved without a password is not encrypted**, so anyone who gets it can read it.
- MuStat does not add its own encryption to the data stored on your phone. Use a screen lock to protect it.

No method of storing or sending data is completely secure.

## How long information is kept, and how to delete it

Your information stays on your phone until you delete it. The troubleshooting log is trimmed automatically, so older entries are removed.

| To delete | Do this |
|---|---|
| Listening history | Settings → **Reset listening history**, for this device or all your paired devices. Your settings, blacklist, custom names, paired devices and troubleshooting log are kept. |
| One import | Remove that import in Settings. |
| A paired device | **Unpair** it in Settings. |
| Everything the app stored | Uninstall MuStat, or clear its storage in Android settings. |

Files you exported, pictures you saved, and data already synced to your other devices stay until you delete them there. With "this device only", the history comes back at the next sync if your other devices still have it.

## If you contact us

If you email us, we receive your email address, your message and anything you attach, such as a log or screenshot. We use it only to answer you and fix the problem. We delete it within 12 months after the conversation ends, or sooner if you ask. The email is handled by our email provider (Google Gmail).

## Your rights

Privacy laws in many places, such as the EU and UK General Data Protection Regulation (GDPR), Thailand's Personal Data Protection Act (PDPA) and California law, give you rights over your personal information. These can include asking to see it, correct it, delete it, get a copy, object to or limit its use, and withdraw consent.

- **Information on your phone** is under your control. You can view it in the app, export a copy, and delete it as described above. We cannot access it.
- **Information you sent us by email:** write to delucamana@gmail.com and we will act on your request.

We do not sell personal information or share it for advertising. You may also complain to the data protection authority where you live.

## Children

MuStat is not directed at children under 13, and we do not knowingly collect information from them. If you believe a child has sent us personal information, contact us and we will delete it.

## Changes to this policy

If this policy changes, we will publish the new version on this page and update the date at the top. This version of MuStat has no ads or payments. If that changes, we will update this policy before releasing the change.

## Contact

delucamana@gmail.com
