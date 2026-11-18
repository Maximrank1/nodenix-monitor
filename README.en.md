# Nodenix Monitor

**Monitoring and maintenance for Apple Silicon Macs**

[Download 0.9.8](https://github.com/Maximrank1/nodenix-monitor/releases/latest) | [Русский](README.md) | [Report a bug](https://github.com/Maximrank1/nodenix-monitor/issues)

I wanted one app for menu bar monitoring and everyday Mac maintenance. That's how Nodenix Monitor started. The app is free.

## What it does

- Menu bar monitoring for CPU load, memory, temperatures, network and disks.
- Available temperature sensors, CPU and GPU clocks, power and fans.
- Mac overview and battery health.
- App removal with a review of related files.
- Cleaning of selected temporary files, browser caches and logs.
- Login items and background service management.

Temperature cards appear only when a sensor returns a valid reading. Missing or unreadable sensors stay hidden. Fan controls are hidden on fanless MacBook Air models.

## Install

Requires an Apple Silicon Mac with macOS 14 or later. You do not need to install Xcode, Homebrew, Python or separate libraries.

1. Download the ZIP from the [latest release](https://github.com/Maximrank1/nodenix-monitor/releases/latest).
2. Extract it and move **Nodenix Monitor.app** to **Applications**.
3. Open the app. Installing the fan control service on compatible Macs requires administrator approval.

The current build has not been notarized by Apple, so macOS may show a warning on first launch.

## Compatibility

Version 0.9.8 was checked on a 13-inch M1 MacBook Pro. A user also checked the sensors and light appearance in 0.9.7 on a 13-inch M4 MacBook Air. Version 0.9.8 improves handling of invalid GPU readings and sensor recognition.

The app discovers available sensors at startup and reads the channels it finds. Available measurements depend on the Mac model and macOS version. Physical testing has not confirmed every M1-M6 variant, including Pro, Max and Ultra models.

## Feedback

[Open an issue](https://github.com/Maximrank1/nodenix-monitor/issues) with your Mac model, macOS version and Nodenix version. Please remove personal information from screenshots.

Source code and version history are kept in a private repository. This repository contains the description and app downloads. Third-party notices are in [ThirdPartyNotices.txt](ThirdPartyNotices.txt).

Nodenix Monitor is free. I may add an optional support link later.
