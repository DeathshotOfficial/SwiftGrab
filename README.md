<div align="center">

# SwiftGrab

**A fast, free download manager for Windows.**
Files, videos and torrents, grabbed at full speed, straight from your browser.

[**⬇ Download for Windows**](https://github.com/DeathshotOfficial/SwiftGrab/releases/latest)

</div>

---

## What it does

- **Faster downloads.** Splits a file into parts and downloads them at the same time. Pause and resume anytime, even after a restart.
- **Videos from almost any site.** YouTube and over a thousand other sites: pick the quality, the audio language, or just the audio (MP3, FLAC, and more).
- **Works where you're signed in.** Videos and files that need a login download with your browser's session, so members-only content works too.
- **Built-in torrent client.** Open magnet links and `.torrent` files, choose which files you want, and set seeding limits.
- **Browser extension.** Downloads you start in the browser go to SwiftGrab automatically, a **Grab Video** button appears on videos, and you can right-click any link and choose **Download with SwiftGrab**.
- **Your rules.** A queue, a scheduler (and shut down or sleep when it's done), speed limits, a proxy, and a list of sites SwiftGrab should leave alone.
- **Looks the way you like.** Several themes plus a theme editor.

No account, no ads, no tracking. See the [privacy policy](PRIVACY.md).

---

## Install

1. Download **SwiftGrab-Setup-*version*.exe** (under **Assets**) from the [latest release](https://github.com/DeathshotOfficial/SwiftGrab/releases/latest).
2. Open it. If Windows shows **"Windows protected your PC"**, click **More info → Run anyway**. That appears because
   SwiftGrab is new and not code-signed yet; it doesn't mean anything is wrong.
3. Pick where to install (the default is fine) and click **Install**. No admin rights are needed.
4. On the last screen, add the browser extension (below), then click **Finish**.

Requires Windows 10 or 11 (64-bit). The video tools (yt-dlp and FFmpeg) are downloaded automatically the first time
they're needed.

## Add the browser extension

The extension connects your browser to SwiftGrab. Install the app first.

| Browser | How |
|---|---|
| **Firefox** | Get it from Firefox Add-ons *(coming soon, in review)* |
| **Microsoft Edge, Chrome, Brave, Opera and other Chromium browsers** | Load it from your PC, see below |

**Edge / Chrome / Brave, step by step**

1. Open `edge://extensions` (Chrome: `chrome://extensions`, Brave: `brave://extensions`).
2. Turn on **Developer mode** (Edge: on the left; Chrome and Brave: top right).
3. Click **Load unpacked** and choose the `extension` folder inside SwiftGrab's install folder.
   By default that's `%LOCALAPPDATA%\Programs\SwiftGrab\extension` (paste that into the folder box).
   The installer's last screen has an **Open folder** button for it.
4. Pin SwiftGrab from the puzzle-piece menu so its button is always visible.

Use that exact folder: SwiftGrab only talks to the extension it installed.

---

## Using SwiftGrab

- **Download a file:** just download it in your browser. SwiftGrab asks where to save it. Press **Cancel** and
  the browser downloads it normally instead.
- **Download a video:** hover the video and click **Grab Video**, or open the SwiftGrab button in your toolbar.
  Choose the quality and click download.
- **Videos that need a login** (Instagram, Facebook, members-only videos): open the video in your browser while
  signed in, then use the **Grab Video** button or right-click the page → **Download with SwiftGrab**.
- **Paste a link:** copy any link and add it in SwiftGrab with the **+** button.
- **Torrents:** click a magnet link or open a `.torrent` file.
- **Keep a site in the browser:** add it under **Settings → Browser → Sites to leave to the browser**.

## Updating

SwiftGrab tells you when a new version is out (**Settings → About**). Download the new installer and run it. Your
settings and downloads are kept.

## Uninstalling

**Windows Settings → Apps → Installed apps → SwiftGrab → Uninstall.** You can choose whether to also delete your
settings and history. Files you downloaded are never deleted. Remove the extension from your browser's extensions
page.

## Problems?

- **The extension says SwiftGrab isn't running:** start SwiftGrab (it can sit in the tray). If you loaded the
  extension from a different folder, remove it and load the `extension` folder from the install folder.
- **A video says it needs a signed-in account:** see "Videos that need a login" above.
- **Something else:** [open an issue](https://github.com/DeathshotOfficial/SwiftGrab/issues) and describe what
  happened. **Settings → Diagnostics** can copy a report to paste in.

---

## Credits

SwiftGrab uses [yt-dlp](https://github.com/yt-dlp/yt-dlp) and [FFmpeg](https://ffmpeg.org) (downloaded from their
official releases when needed) and [MonoTorrent](https://github.com/alanmcgovern/monotorrent).

SwiftGrab is free to use. The source code is not public. See [LICENSE](LICENSE).
