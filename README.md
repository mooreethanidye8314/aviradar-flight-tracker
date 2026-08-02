# AviRadar - Flight Radar 2026

> **AviRadar is a web-based flight tracker for viewing live ADS-B aircraft activity around Ismaning. It supports several distance filters and adapts to both desktop and mobile screens.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mooreethanidye8314/aviradar-flight-tracker?style=flat-square)](https://github.com/mooreethanidye8314/aviradar-flight-tracker)

---

<p align="center">
  <a href="https://mooreethanidye8314.github.io/aviradar-flight-tracker/">
    <img src="https://img.shields.io/badge/Download-AviRadar%20Latest-brightgreen?style=for-the-badge" alt="Download AviRadar">
  </a>
</p>

> **[Download AviRadar](https://mooreethanidye8314.github.io/aviradar-flight-tracker/)**

---

[Download Latest Build](https://mooreethanidye8314.github.io/aviradar-flight-tracker/)

---

## Overview

AviRadar concentrates on aircraft traffic in the area surrounding Ismaning. Live ADS-B data is displayed on an OpenStreetMap-based map, giving aviation enthusiasts, nearby observers, and other users an accessible way to watch local air traffic.

Alongside the map view, the application presents aircraft-specific information and lets users choose how far from Ismaning they want to monitor. Everything runs in the browser, with no dedicated desktop application required. When the public data service cannot be contacted, AviRadar can fall back to a demo mode.

---

## What It Offers

- Monitor aircraft located within 25, 50, 75, or 100 nautical miles of Ismaning.
- Inspect callsign, aircraft type, registration, altitude, speed, heading, and squawk values.
- Receive an automatic aircraft-data refresh every 15 seconds.
- Continue exploring the interface in demo mode if the public ADS-B API is unavailable.
- See aircraft locations on OpenStreetMap.
- Retrieve live aviation information from the ADSB.lol API.
- Use the layout on desktop systems as well as smartphones.
- Select a smaller local radius or expand the view to cover surrounding air traffic.

---

## Getting Started

AviRadar runs directly in a web browser. To create a local copy, clone the repository:

```bash
git clone https://github.com/mooreethanidye8314/aviradar-flight-tracker.git
cd REPO
```

Start the resulting directory with any static web server and open the local address it provides in a current browser. You can also use the hosted version:

[Open AviRadar](https://mooreethanidye8314.github.io/aviradar-flight-tracker/)

As an HTML browser application, AviRadar does not need a desktop installer or a separate runtime package for standard operation.

---

## Using AviRadar

1. Launch AviRadar in a supported modern browser.
2. Set the monitoring distance to 25, 50, 75, or 100 nautical miles.
3. Browse aircraft around Ismaning on the map.
4. Choose an aircraft or review its displayed information, such as callsign, registration, type, altitude, speed, heading, and squawk.
5. Let the application update the aircraft list automatically every 15 seconds.
6. Switch to demo mode if the public live-data API cannot be reached.

---

## Settings and Data Sources

The main configuration is available through AviRadar's controls in the browser. Change the tracking radius with the range selector to modify the map coverage.

When hosted locally, settings remain part of the web project instead of being managed through a separate desktop preferences application. Aircraft data comes from the ADSB.lol API, and the map is rendered with OpenStreetMap.

---

## System Requirements

- A current desktop or mobile web browser.
- Internet connectivity for map assets and live ADS-B information.
- Availability of the ADSB.lol public API for live aircraft data.
- JavaScript enabled.
- A static web server for serving a local repository checkout.
- A connection capable of supporting data updates at approximately 15-second intervals.

---

## Frequently Asked Questions

### Which location does AviRadar cover?

The application centers its view on Ismaning and lets you select a radius of 25, 50, 75, or 100 nautical miles.

### What information can I see for an aircraft?

Available fields include the callsign, aircraft type, registration, altitude, speed, heading, and squawk.

### At what interval is aircraft data updated?

AviRadar automatically requests refreshed aircraft information every 15 seconds.

### Can I use the application without live API data?

Yes. Demo mode is available when the public ADSB.lol API cannot provide live information.

### Is a normal software installation necessary?

No. Open the hosted browser build, or serve the HTML project locally through a static web server.

### What should I check if the map or aircraft are missing?

Confirm that your internet connection is working, JavaScript is active, and the public data service can be reached. If live data is still unavailable, use demo mode.

### How can I change the monitored area?

Open the radius selector and choose the required distance from Ismaning.

### Where are new versions and changes published?

Use the hosted build, and review the project repository for subsequent changes and published versions.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
