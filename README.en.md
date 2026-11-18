# Nodenix Monitor

**Monitoring and maintenance for Apple Silicon Macs**

[Download 0.9.8](https://github.com/Maximrank1/nodenix-monitor/releases/latest) | [Русский](README.md) | [Report a bug](https://github.com/Maximrank1/nodenix-monitor/issues)

I made Nodenix Monitor because I wanted to see what my Mac was doing straight from the menu bar. Temperatures, CPU load, memory and network activity are all in one place. I later added tools for cleaning up files and removing apps. The app is free.

## What it does

- Shows CPU load, memory, temperatures, network activity and disks in the menu bar.
- Shows the sensors it finds, CPU and GPU clocks, power readings and fans.
- Shows Mac details and battery health.
- Helps find files related to an app before removing it.
- Lets you choose temporary files, browser caches and logs to clean up.
- Shows login items and background services.

A temperature card appears when a sensor is available and returns a valid reading. If macOS cannot read a sensor, I leave that card out. Fan controls are hidden on fanless MacBook Air models.

## Install

You need an Apple Silicon Mac with macOS 14 or later. There is no need to install Xcode, Homebrew, Python or separate libraries.

1. Download the ZIP from the [latest release](https://github.com/Maximrank1/nodenix-monitor/releases/latest).
2. Extract it and move **Nodenix Monitor.app** to **Applications**.
3. Open the app. Installing the fan control service requires administrator approval.

This build has not been notarized by Apple yet, so macOS may show a warning the first time you open it.

## Macs checked so far

I checked the 0.9.8 build on a 13-inch M1 MacBook Pro. A friend checked the sensors in 0.9.7 on a 13-inch M4 MacBook Air. In 0.9.8, I improved the handling of invalid GPU readings and sensor recognition.

The available sensors vary by Mac. I have not been able to check every M1-M6 model, including Pro, Max and Ultra versions. I cannot promise that every sensor will appear on every Mac.

## Found a bug?

Open an [issue](https://github.com/Maximrank1/nodenix-monitor/issues) with your Mac model, macOS version and Nodenix version. A screenshot helps too, but please remove personal information first.

I keep the source code and version history in a private repository. This one has the description and app downloads. Third-party notices are in [ThirdPartyNotices.txt](ThirdPartyNotices.txt).

If I add a way to support development later, I will put a link here. For now, the app is free to use.
