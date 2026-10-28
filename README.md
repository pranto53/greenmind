# Greenmind

**[⬇ Download Greenmind for Android](https://github.com/pranto53/greenmind/releases/latest/download/Greenmind.apk)**
· Android 8.0 or newer · free, no ads

Counts the shorts and reels you watch in YouTube, TikTok, Instagram, Facebook and Chrome, warns you at your
limits, and locks shorts once you've had enough. Strict mode stops you from raising your limits, switching them or the
app off or uninstalling it until it ends.

**Private by design:** you sign in with Google once, which needs the internet; after that the app works offline.
Your name and email address are all that leave your phone: nothing the app sees does. It never stores what is on
your screen: a short is saved only as an anonymous digest, to count it once.

Greenmind isn't affiliated with or endorsed by YouTube, TikTok, Instagram or Facebook. Their names belong to
their owners.

## Install

1. Tap **[Download Greenmind](https://github.com/pranto53/greenmind/releases/latest/download/Greenmind.apk)** on
   your phone and open the file.
2. Your phone asks to allow installing apps from your browser (or Files app): allow it.
3. Play Protect may say **App scan recommended**, because it hasn't seen Greenmind before. Tap **Scan app**
   (Google checks it and then installs it), or **More details › Install without scanning** (your phone asks for
   your fingerprint or PIN).
4. Open Greenmind and follow its setup pages: turn on accessibility (that is how it sees which video is on
   screen) and let it run in the background.

**"Restricted setting" when turning on accessibility?** Android 13 and newer do this for apps installed from a
download. Open Settings › Apps › Greenmind, tap **⋮ › Allow restricted settings**, then turn accessibility on
again. The setup page takes you there.

## Updates

When a new version is out, Greenmind tells you with a popup as you open it. Tap **Download** and install it over
the one you have: your counts and settings are kept. (Version 1.0.0, called Shorts Counter, doesn't do this yet:
download the new version once from the link above.)

**After updating, open Greenmind.** Android switches accessibility off for an app updated from a downloaded
file, so nothing is counted or locked until you turn it back on. The app asks for it as it opens; you may need
**⋮ › Allow restricted settings** in its App info again first.

All versions are on the [Releases page](https://github.com/pranto53/greenmind/releases).

## Strict mode

While strict mode is on, a limit that is switched on can only go down and can't be switched off (one that
is off can still be changed either way), and Greenmind closes its own App info page (Uninstall,
Force stop, Clear data), its accessibility page and its device admin page. Uninstalling is stopped by making it a
device admin: it asks for no powers (it can't lock or erase your phone) and switches itself off when strict mode
ends.

Updates still install during strict mode. Installing one switches accessibility off (see Updates), and until it
is back on, strict mode can't lock anything.

It ends when its time is up, or with its password. Forgot the password? **Forgot password?** ends strict mode 24
hours later. Changing the phone's clock doesn't end it sooner.

## Known limits

- **Facebook** (the full app) reels are found by an English label: with the phone in another language, they
  aren't counted.
- Apps in a work profile or Samsung's Secure Folder can't be seen.
- Phones in safe mode run no downloaded apps, Greenmind included.

## Feedback

Found a problem or have an idea? [Open an issue](https://github.com/pranto53/greenmind/issues), or use
Settings › Send feedback in the app.

---

© 2026 pranto. All rights reserved. Greenmind is free to download and use; its code is not open source.
