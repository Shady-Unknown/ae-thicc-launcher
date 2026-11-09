 <img src="DiscoveryTab.png" height="120" /><img src="Schermata_20260607_000113.png" height="120" /> <img src="AeThiccLauncherLogoBig.png" width="120" /> <img src="Schermata_20260607_000046.png" height="120" />



# TO INSTALL (LINUX)
_flatpak install --user Ae_Thicc_Launcher_Linux.flatpak_

Remember to Install ffmpeg to have game trailers working in the brand new "Discovery" view!

Trailers play out of the box. To also get smooth seeking on Linux, install `ffmpeg` with your distribution's package manager:

| Distribution | Command |
|---|---|
| Debian / Ubuntu / Mint / Pop!_OS | `sudo apt install ffmpeg` |
| Fedora | `sudo dnf install ffmpeg` |
| Arch / Manjaro / EndeavourOS | `sudo pacman -S ffmpeg` |
| openSUSE | `sudo zypper install ffmpeg` |

# TO INSTALL (Windows)
_Simply extract wherever you see fit and launch. Default paths point to common applications data folders by default, but you can change them in the settings_


# Ae Thicc Launcher (Unofficial SteamRIP Client)

Welcome to **Ae Thicc Launcher**, the ultimate desktop companion designed to seamlessly manage, download, and update your games library. 

This launcher doesn't just have an aesthetic; it has a **purpose**. 

In an industry increasingly dominated by the **aggressive monetization** of big corporations, **game preservation** and accessibility have never been **more critical**. **Ae Thicc Launcher** was built to ensure that everyone, regardless of their current financial capability, can access, play, and retain the games they love. We care deeply about true software ownership, giving you the tools to preserve your game files and your hard-earned savegames forever.

However, this freedom comes with a strong moral compass. We believe in voting with our wallets and supporting those who respect the medium. Our core motto, and the driving force behind this project, is simple:

> **"If a Developer or Publisher isn't aggressively monetizing, if they care about the customer and support them, THEN BUY THE GAME. THEY DESERVE IT."**

While many of our ethical features are still actively being developed behind the scenes, everything we build aims to strike this balance: do what you want with YOUR software, but always remember to reward the non-toxic, passionate developers who make this industry great.

## Community

<a href="https://discord.gg/4WF7YU3ynC"><img src="discorda.jpg" width="80" align="left" alt="Ae Thicc Launcher Discord" /></a>

**Join the Ae Thicc Launcher Discord** — get help with setup, report bugs, suggest features, or just hang out and talk games.

**[discord.gg/4WF7YU3ynC](https://discord.gg/4WF7YU3ynC)**

<br clear="both" />

---
## UPCOMING

*   **ESRB:** I'm about to be one of those who's gonna make a ton of dad jokes. It's not much, we care about privacy as much as we care about your children being safe, and you being a parent
*   **Cloud Saves Sync**: Having your games saved on the cloud (your own personal GDrive or similar) will make things twice as easy once you format, or move on with different games.


## Key Features

### Discovery
*   **Doomscroll the catalog:** a single-row horizontal scroller that never ends. Pick a category, keep scrolling, find the game you'll install at 3 AM.
*   **Per-category browsing:** Trending, New Releases, Recently Added, Recently Updated and every SteamRIP category, one at a time, with a jump selector when you already know where to go.
*   **Search anything:** type a few characters and get one row with every matching game across the whole catalog.
*   **All games:** the entire catalog in one endless row, newest SteamRip releases first — nothing is left out, even the oldest titles.
*   **Sort where it makes sense:** Trending and My Library can be ordered by title, SteamRip added date, release date or rating. Date-based rows (New Releases, Recently Added/Updated, the SteamRIP categories and All Games) always keep their own order.
*   **Game cards:** one click opens the full sheet — cover, rating, genres, themes, game modes, developer, publisher, platforms, description, PEGI/ESRB age ratings and SteamRIP vs Steam build.
*   **Install in one click:** the *Install* button opens the game in the Games Explorer with its download links ready.
*   **Built-in trailer player:** fullscreen, volume, mute and smooth seeking; trailers are cached locally, so repeat views start instantly.

### Smart Explorer & Downloader
*   **Integrated Catalog:** Instantly search through the entire SteamRIP database with a lightning-fast auto-completing search bar.
*   **Cloudflare Bypass:** A stealthy, built-in browser handles Cloudflare challenges automatically whenever possible, so your downloads never get stuck.
*   **Smart Resume**: if the provider supports it you can resume your download, even between sessions. Low bandwidth? Latency or unstable connections? We got you. Just press "play" again and the download will resume from where it stopped
*   **Auto-Extraction & Installation:** Games are downloaded, automatically extracted, and neatly placed into your designated "Watched Folders".


### Advanced Library Management
*   **Orphan Recovery:** Found an old folder? The launcher can automatically scan it, fetch the correct metadata from the web, and populate it into your library.
*   **Update Checker:** Compares your local game version against the web version. If a new update is available, it notifies you and helps you download the games directly (no patch files supported now, unless specified by the host game's page)
*   **Digital Store Links:** Automatically grabs official Steam and GOG store links so you can check out the official pages.
*   **Steam Sales Mirror:** You got that game in your library. It's SO GOOD! And the devs? You heard great about them. We'll let you know when that piece of art is for sale on **STEAM** and/or **GOG** (nope, F* off Epic)
*   **Gold Tier:** Games from known Software Houses, verified by the community, in which you can rely forever. Non Toxic, Non Predatory, Quality made games that deserves a spotlight

### Savegames Manager
*   **Ludusavi Integration:** Automatically fetches game informations to locate exactly where your game saves are stored, both for Windows and Linux (Proton) prefixes.
*   **Automated Backups:** Set a sync interval or let the launcher do the work. The built-in **Process Monitor** detects when you close a game and immediately backs up your latest save securely.
*   **Versioning:** Keeps a rotating history of your last 3 save snapshots, so you can always roll back if your file gets corrupted.

### Steam Integration & Linux/Deck Support
*   **One-Click Steam Injection:** Add your non-Steam games directly into your Steam Library with a single click.
*   **Automated Artwork:** The launcher downloads and applies Covers, Heroes, and Logos to your Steam Library entries dynamically!
*   **Proton Ready:** On Linux/Steam Deck, the launcher automatically configures Steam shortcuts to use `Proton GE` or `Proton Experimental`, getting you ready to play immediately.

---


## Getting Started & Setup

1.  **Configure Watched Folders:** Upon your first launch, head to the **Configuration Panel** under the **Settings** Menu. Add at least one "Watched Folder" (e.g., `C:\Games` or `/home/deck/Games`). This is where the launcher will scan for installed games and extract new downloads.
2.  **Configure Save Sync Folder:** In the settings, designate a folder where your savegame backups will be stored (default no forced designation, it has a default path OS based)
3.  **Search & Play:** Go to the Explorer tab, type a game name or paste a VALID URL (wink wink), hit Enter, and let the launcher do the heavy lifting!

### ffmpeg on Linux (trailer seeking)
Trailers play out of the box. To also get smooth seeking on Linux, install `ffmpeg` with your distribution's package manager:

| Distribution | Command |
|---|---|
| Debian / Ubuntu / Mint / Pop!_OS | `sudo apt install ffmpeg` |
| Fedora | `sudo dnf install ffmpeg` |
| Arch / Manjaro / EndeavourOS | `sudo pacman -S ffmpeg` |
| openSUSE | `sudo zypper install ffmpeg` |

On **Steam Deck (SteamOS)** the system is immutable: use `sudo steamos-readonly disable && sudo pacman -S ffmpeg && sudo steamos-readonly enable` (it may need to be repeated after a SteamOS update), or run the launcher from a distrobox/container that has ffmpeg.

On **Windows** nothing is needed: the launcher bundles what it requires.

In the **Flatpak** build the launcher runs inside a sandbox: seeking works if `ffmpeg` is available there, otherwise the trailer streams normally without seeking.

---

## Technical Notes for Power Users
*   **Metadata:** Game metadata is stored locally inside each game's folder in a `steamrip_meta.json` file. You can back up your games just by moving the folder; the launcher will recognize them instantly on the next scan.
*   **Cache:** The Master Catalog caches locally and updates in the background to prevent unnecessary network requests.
*   **Network Drops:** The smart downloader supports resume functionality. If your connection drops, it will automatically attempt to resume up to 10 times. Results may vary depending on hosts.
*   **Trailers:** the first time a trailer is opened it is prepared in a local cache so seeking is instant and repeat views start immediately. On Windows the needed tool is bundled; on Linux install `ffmpeg` (see above) to enable seeking.

---

## What's New in Version 1.6.1?
# Discovery
- New **Recently Added** row: the newest SteamRip arrivals, in the same order as the site.
- **Search the whole catalog:** from two characters the search row matches every title in the master catalog (5,000+), not only the cards already loaded.
- New **All Games** row: the entire catalog in one endless row, newest SteamRip releases first and the rest alphabetical.
- **Covers load while you scroll:** rows fetch artwork for the cards that come into view, use the SteamRip page image as a fallback and fall back to a SteamGridDB title lookup for games without a Steam app id.
- **Sort where it makes sense:** a dropdown orders Trending and My Library by title, SteamRip added date, release date or rating. Date-based rows (New Releases, Recently Added/Updated, the SteamRIP categories and All Games) always keep their own order.
- **Calmer scrolling:** a 6 px dead zone before a drag starts, a cap on the flick speed, and touchpads no longer jump a row with tiny scrolls.
- Hover feedback returns as soon as a drag or scroll settles.

---
