# SwiftGrab Privacy Policy

_Last updated: 20 October 2026_

SwiftGrab is a download manager made of two parts: the **SwiftGrab Desktop** app for Windows and the
**SwiftGrab browser extension** for Microsoft Edge, Mozilla Firefox and other Chromium browsers. This policy
covers both.

## The short version

SwiftGrab does not collect, sell or share your data. There are no accounts, no analytics, no advertising and no
tracking. Everything the extension handles is passed only to the SwiftGrab Desktop app running on your own
computer.

## What the extension handles, and why

When you download a file or a video, the extension reads the following and hands it to SwiftGrab Desktop on the
same computer (through the browser's native messaging channel or a connection to `127.0.0.1`, which never
leaves your PC):

- **The address of the file or video**, and the address and title of the page it came from, so SwiftGrab can
  download it and name it.
- **The cookies for that website**, so files and videos that need you to be signed in (for example a members-only
  video, or a site behind a login) download with your session, just as they would in the browser.
- **Your browser's user agent and the request headers of the media**, so the website serves SwiftGrab the same
  file it would serve your browser.

The extension also detects videos on the page you are viewing so it can show its "Grab Video" button. This
happens inside your browser; nothing about the pages you visit is recorded or sent anywhere.

Your extension settings (for example sites where SwiftGrab should not take over downloads) are kept in the
browser's own extension storage on your computer.

## What the desktop app does

SwiftGrab Desktop stores your settings, download history and the cookies it was given for a download on your
computer only. It connects to the internet only to:

- download the files, videos and torrents you ask for, from the sites they come from;
- check GitHub for a newer version of SwiftGrab;
- download and update its helper tools (yt-dlp and FFmpeg) from their official GitHub release pages;
- when you run Diagnostics, test your internet connection by contacting Cloudflare's public `1.1.1.1` address.

None of these requests include your downloads, history or cookies, except that a download request to a website
carries that website's own cookies, as described above.

## Removing your data

Uninstalling SwiftGrab offers to delete your settings, download history and saved site logins. Removing the
browser extension removes its settings from your browser. Files you downloaded are never deleted.

## Contact

Questions about this policy: open an issue at https://github.com/DeathshotOfficial/SwiftGrab/issues.
