# Hot Bottom Smoker

An Android app for monitoring and controlling **Pit Boss vertical pellet smokers** (built and tested for the PBV4NX). It's a personal, unofficial replacement for Pit Boss's Smoke IT app and has no connection to Pit Boss or Dansons.

## ⬇️ Download

**[Download the latest version (HotBottomSmoker.apk)](https://github.com/GillSLOW/HotBottomSmoker/releases/latest/download/HotBottomSmoker.apk)**

Older versions are on the [Releases page](https://github.com/GillSLOW/HotBottomSmoker/releases).

## Installing (Android only)

1. Open the download link above **on your Android phone**.
2. Tap the downloaded file. If Android asks, allow your browser or Files app to **install unknown apps**. This happens once.
3. If Google Play Protect warns that it doesn't recognize the app, tap **More details → Install anyway**. It warns because the app doesn't come from the Play Store.
4. To update later, download and install the newest version the same way. It installs over the old one and keeps your cooks and settings.

Requires Android 8.0 or newer. This is an Android app, so it won't run on an iPhone.

## First use

1. **Fully close the Pit Boss app**: swipe it away from recent apps. The smoker allows only one Bluetooth connection at a time.
2. Turn the smoker on and stand near it.
3. Open Hot Bottom Smoker, tap **Smoker…** and pick your smoker. It usually shows a ★ and a name starting with "PB".
4. Tap **Start logging**. You can lock the phone now, because logging continues in the background.

## What it does

- Live cabinet temperature and up to 3 meat probes, with a graph of the **whole cook**
- Changes the set temperature, shuts the smoker down, and primes the auger (with safety limits)
- **Reliable Bluetooth** that reconnects on its own, low battery use over long cooks
- **Remote monitoring** over the internet when you're away (the smoker must be on Wi-Fi)
- Alerts for probe targets, temperature drift, errors, a fire that's going out, and lost connection
- Outside weather at the smoker, cook history with CSV export, pellet estimates, and hours tracking for parts
- Shows the shutdown cycle in progress, even though the smoker's own screen goes dark

## Notes

- It's built for the PBV4NX and should work with other Pit Boss vertical smokers that use the same controller. On other Pit Boss grills, some features may not work.
- Use it at your own risk. It's a hobby project, provided as-is.
- The smoker protocol code is based on the open-source [pytboss](https://github.com/dknowles2/pytboss) project (Apache License 2.0). See `NOTICE` and `LICENSE-pytboss.txt`.
