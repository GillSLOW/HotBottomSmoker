# Hot Bottom Smoker

An Android app for monitoring and controlling **Pit Boss pellet smokers**: the PBV4NX vertical (tested) and the PB1285KC grill (new, not yet tested on real hardware). It's a personal, unofficial replacement for Pit Boss's Smoke IT app and has no connection to Pit Boss or Dansons.

## ⬇️ Download

**[Download the latest version (HotBottomSmoker.apk)](https://github.com/GillSLOW/HotBottomSmoker/releases/latest/download/HotBottomSmoker.apk)**

Older versions are on the [Releases page](https://github.com/GillSLOW/HotBottomSmoker/releases). If the link above doesn't work, use this direct link: [HotBottomSmoker.apk](https://github.com/GillSLOW/HotBottomSmoker/raw/main/apk/HotBottomSmoker.apk)

## Installing (Android only)

1. Open the download link above **on your Android phone**.
2. Tap the downloaded file. If Android asks, allow your browser or Files app to **install unknown apps**. This happens once.
3. If Google Play Protect warns that it doesn't recognize the app, tap **More details → Install anyway**. It warns because the app doesn't come from the Play Store.
4. To update later, download and install the newest version the same way. It installs over the old one and keeps your cooks and settings.

Requires Android 8.0 or newer. This is an Android app, so it won't run on an iPhone.

## First use

1. **Fully close the Pit Boss app**: swipe it away from recent apps. The smoker allows only one Bluetooth connection at a time.
2. Turn the smoker on and stand near it.
3. Open Hot Bottom Smoker, tap **Connect** and pick your smoker. It usually shows a ★ and a name starting with "PB".
4. It connects and starts logging right away (temperatures and weather appear). You can lock the phone now, because logging continues in the background. **Disconnect** ends the cook.

## What it does

- Live cabinet temperature and up to 3 meat probes, with a graph of the **whole cook**
- Changes the set temperature, shuts the smoker down, and primes the auger (with safety limits)
- **Reliable Bluetooth** that reconnects on its own, low battery use over long cooks
- **Remote monitoring** over the internet when you're away (the smoker must be on Wi-Fi)
- Alerts for probe targets, temperature drift, errors, a fire that's going out, and lost connection
- Outside weather at the smoker, cook history with CSV export, pellet estimates, and hours tracking for parts
- Shows the shutdown cycle in progress, even though the smoker's own screen goes dark

## Reporting a problem

In the app, go to **Settings → Troubleshooting → Send to developer (GitHub)**. It copies a debug report to your clipboard and opens a new issue here. Say what happened, then **long-press in the text box and choose Paste**, and tap **Create**. Paste it rather than attaching a file, because pasted text is what the developer can read. You'll need a free GitHub account. Issues are public, but the report blanks out passwords, location and most of the cloud ID.

## Notes

- Models: every Pit Boss and Louisiana Grills model in the Dansons catalog (140+, as published by [pytboss](https://github.com/dknowles2/pytboss)). Tested on real smokers: PBV4NX (130–420°F, 3 probes) and PB1285KC (Smoke 180°F – High 500°F, 2 probes, light). Pick yours when you choose the smoker, or later in Settings (Change model…). If yours isn't listed or you're not sure, choose "Not sure": the app reads the control board from the smoker's Bluetooth name and works out the temperature range from the controller as you cook. Other models haven't been tested on real hardware yet, so please send a debug report from your first cook.
- Choosing the smoker: long-press Connect. The list is a live Bluetooth scan: a smoker appears as soon as it's plugged in, and yours is marked ✓.
- Use it at your own risk. It's a hobby project, provided as-is.
- The smoker protocol code is based on the open-source [pytboss](https://github.com/dknowles2/pytboss) project (Apache License 2.0). See `NOTICE` and `LICENSE-pytboss.txt`.
