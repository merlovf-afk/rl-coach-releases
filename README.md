# RL Coach

A coaching app for Rocket League that reads your own saved replays on your own PC.
This page holds the installer and the update files, nothing else.

## Install

1. Download **RLCoachApp-win-Setup.exe** from the [latest release](../../releases/latest).
2. Run it. Windows shows "Windows protected your PC", because the installer is not signed yet. Click **More info**, then **Run anyway**.
3. The app opens, finds your Rocket League replay folder by itself and starts reading your saved replays. The first time takes a few minutes.

It needs Windows 10 or 11 (64-bit) and about 500 MB of disk. It does not need admin rights.

The game only saves a replay when you save it, so save the games you want looked at.

## Updates

An installed copy updates itself. When the app starts it asks this page whether a newer version exists and fetches it in the background. The new version is put in place the next time the app is closed or started, never while Rocket League is running.

## What stays on your PC

Your replays, your numbers and your settings are kept in `%LOCALAPPDATA%\RLCoach` and are not sent anywhere.

Two things reach the internet without you asking:

- **The update check.** It goes to github.com and carries the installed version, the app's install name and a random number made when the app was installed. Nothing about you or your games.
- **The typeface.** The app's window loads its lettering from Google Fonts, as many web pages do.

The match recorder and the live window are off until you switch them on under the gear, in "Runs by itself".

## Remove it

Windows Settings, Apps, RL Coach, Uninstall. Your library in `%LOCALAPPDATA%\RLCoach` is left alone. Delete that folder as well if you want everything gone.

---

RL Coach is a hobby project and comes with no warranty. It is built with open-source libraries, listed in `THIRD-PARTY-NOTICES.txt` in the program folder. Rocket League is a trademark of Psyonix LLC. RL Coach is not made by, or connected with, Psyonix or Epic Games.
