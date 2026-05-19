<h1 align="center">
  <br>
  <a href=""><img src="https://raw.githubusercontent.com/srhady/Hady/refs/heads/main/.photo/tapmadnewcoveer_e663773d-773b-41f7-a3cb-e896ad99fa55-686.jpeg" alt="Tapmad Metadata" width="120"></a>
  <br>
  Tapmad Live Matches & Metadata Indexer
  <br>
</h1>

<h2 align="center">An automated API wrapper to fetch live match schedules, metadata, and dynamic stream manifests directly from Tapmad.</h2>

</a>
  <a href="">
      <img src="https://raw.githubusercontent.com/srhady/Hady/refs/heads/main/.photo/IMG_20260520_001513.jpg" width="60%">
  </a>
​<p align="center">
<img src="https://img.shields.io/badge/Made_With-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Made%20in-Bangladesh_🇧🇩-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge" alt="Bangladesh">
</p>

# 📒 Introduction

**Tapmad Auto-Indexer** is a lightweight Python script that acts as an API wrapper. It automatically scrapes and indexes publicly available metadata, live schedules, and stream manifests (`.m3u8` / `.mpd`) from Tapmad. 

⏱️ Powered by **GitHub Actions**, the script runs periodically to ensure the generated schedule and manifest links are always fresh. It outputs the formatted data into both **JSON** (for developers/frontend) and **M3U** (for media players) formats.

📡 Easily track schedules for major live events, including **Football, Cricket, Basketball, Tennis**, and more.

> ⚠️ For educational, research, and personal use only. Please read the Legal Disclaimer below.

# 💥 Key Features

* 🔄 **Fully Automated:** Periodically fetches and updates match metadata.
* 📦 **Dual Output:** Generates clean `tapmad_bd.json` for API usage and `tapmad_bd.m3u` for direct media playback.
* ⚡ **Smart Caching:** Minimizes server requests by caching unchanged endpoints via ETags (304 Not Modified).
* 🛡️ **Clean Extraction:** Extracts clean manifest URLs from the platform's Web API.
* 🚀 **Plug & Play:** Ready to be parsed by any frontend application or standard IPTV player.


# 🕹️ How To Use

**For Users (Media Players)**
* 👉 **[Auto Updated M3U Playlist File](https://raw.githubusercontent.com/srhady/tapmad-bd/refs/heads/main/tapmad_bd.m3u)**
* Add this raw link directly to your preferred media player.

**For Developers (Frontend/API)**
* 👉 **[Auto Updated JSON File](https://raw.githubusercontent.com/srhady/tapmad-bd/refs/heads/main/tapmad_bd.json)**
* Use this JSON file to build your own sports schedule UI or frontend application.

# 🎬 How To Play

**📱 Android / iOS**
* Use **Network Stream Player** or **OTT Navigator**.
* Add This PlayList URL: `https://raw.githubusercontent.com/srhady/tapmad-bd/refs/heads/main/tapmad_bd.m3u`

**🖥️ Android TV / Smart TV**
* Use **TiviMate** or **Televizo**.
* Add This PlayList URL: `https://raw.githubusercontent.com/srhady/tapmad-bd/refs/heads/main/tapmad_bd.m3u`

<p align="center">
  <img src="https://raw.githubusercontent.com/srhady/Hady/refs/heads/main/.photo/Screenshot_20260520_002418.jpg">
  <img src="https://raw.githubusercontent.com/srhady/Hady/refs/heads/main/.photo/Screenshot_20260520_002503.jpg">
</p>


# 🚬 Author 
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=100&color=FF2C10&background=31FF9400&width=400&lines=DEVELOPED+BY+HADY)](https://git.io/typing-svg)

# ⚠️ Legal Disclaimer & DMCA

This repository and its author do not host, store, stream, or distribute any copyrighted video, media, or broadcasting content. 

* This project is strictly for **educational and research purposes**, demonstrating how to parse web metadata and automate the generation of structured JSON/M3U files using Python.
* The script merely acts as a search engine/scraper that fetches publicly accessible metadata and URLs. All video content is hosted by third-party servers and streaming providers.
* We do not own, manage, or control the servers that host the media. Thus, we cannot be held responsible for the content, compliance, copyright, legality, or decency of the linked streams.
* This repository is not meant for commercial use or sale.

**To Copyright Owners:** If you believe that any content linked here infringes upon your copyright, please understand that this repository does not host the files. Please send your DMCA takedown requests directly to the third-party media hosts. However, if you want any specific metadata or link removed from this indexing repository, please contact us via Telegram or open an Issue, and it will be removed immediately without the need for a DMCA strike.

# 📝 Note
* Do not use this repository for any illegal or harmful activities.
* Please give proper credit if you fork or share this content.
* The core source code of this repository is strictly obfuscated to ensure security and prevent unauthorized modifications. 

# ✉️ Find Me on 

- [![Github](https://img.shields.io/badge/Github-SRHADY-purple?style=for-the-badge&logo=github)](https://github.com/srhady)

- [![Telegram](https://img.shields.io/badge/Telegram-LiveSportsPlay-indigo?style=for-the-badge&logo=telegram)](https://t.me/livesportsplay)
