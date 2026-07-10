# Changelog

All notable changes to EliteGDX are documented here.

## 📜 Version 4.2 Change Log (Celestial Update) – July 2026

| Date | Change |
|------|--------|
| 2026‑07‑10 | **Celestial Clock** – New mode combining glass analog clock with cosmic wheel overlay. |
| 2026‑07‑10 | **Flat Earth Projection** – Added stretched elliptical view with day/night spotlight. |
| 2026‑07‑10 | **Ephemeris System** – External JSON fetch with fallback for long‑term planetary accuracy. |
| 2026‑07‑10 | **Mirror Mode** – Full support for all 6 clock modes (Classic, Glass, Digital, Cistercian, Cosmic, Celestial). |
| 2026‑07‑10 | **Clean View** – Full support for hiding controls in Cosmic, Celestial, and Flat Earth modes. |
| 2026‑07‑10 | **Cosmic Wheel** – Standalone cosmic canvas now scales with `50vw` (separate from celestial overlay). |

### Added
- **Celestial Clock** – Glass analog clock overlaid on the Cosmic Wheel.
- **Flat Earth Projection** – Two views (circular & stretched) with day/night spotlight.
- **Ephemeris System** – External JSON fetch with fallback for long‑term planetary accuracy.
- **Mirror Mode** – Full support for all 6 clock modes.
- **Clean View** – Full support for Cosmic, Celestial, and Flat Earth modes.

### Fixed
- Celestial mode centering in mirror mode.
- Mobile mirror mode override for celestial clock.
- Flat earth controls restore gap after clean view full.
- Cosmic canvas negative radius error.

---

## 📜 Version 4.1 Change Log (Remote Viewing Update) – May 2026

| Date | Change |
|------|--------|
| 2026‑05‑23 | **Remote Viewing Commands** – `remoteview`, `grabimg`, `fetchpage`, `portal`. |
| 2026‑05‑23 | **IPTV Enhancements** – Personal `ipset` list, HLS.js support, copy URL button. |
| 2026‑05‑23 | **Portal Shortcuts** – `elitegdx`, `famelack`, `radiogarden`, `f1`, `flightradar24`, `opensea`, `earthcam`, `azmth`, `heavens`, `keeptrack`. |
| 2026‑05‑22 | **ESP & Clairvoyance Commands** – Conceptual additions for cyber‑reconnaissance. |
| 2026‑05‑21 | **CORS Proxy** – All remote commands use `api.allorigins.win` to bypass cross‑origin restrictions. |

### Added
- `remoteview`, `grabimg`, `fetchpage`, `portal` commands.
- Personal `ipset` IPTV list.
- Portal shortcuts for live feeds and satellites.
- HLS.js support and copy URL button.

### Fixed
- YouTube player container race condition.
- IPTV timeout false alarms.
- XSS vulnerabilities in chat and remote commands.

---

## 📜 Version 4.0 Change Log(CyberOps) (May 2026)

The "Akashic Update" transforms the dashboard into a comprehensive information retrieval & cyber‑operations hub, with over 40 new commands, a full cipher suite, media playback, and live data feeds.

| Feature | Description | Interaction |
| :---    | :---        | :---        |
| **Command Runner** | Built‑in terminal with sync/async router, HTML output, and fullscreen mode. | `💻 Command Runner` button, `⛶ Fullscreen` |
| **Login & Identity** | Majestic Akashic splash with rotating header, typewriter names, and `whoami` personas. | Auto on terminal open, `login`, `whoami`, `motd`, `about` |
| **News & Information** | BBC World News, Hacker News, curated tech headlines, weather. | `news`, `hackernews`, `technology` |
| **Dictionary & Learning** | Full phonetic dictionary, physics/math formulas, electronics facts, engineering marvels, biology, space, CS tips. | `define`, `physics`, `electronics`, `engineering`, `biology`, `space`, `cstip`, `learn`, `fortune` |
| **Engineering Diagnostics** | Resistor calculator, color code decoder, Ohm's Law, voltage divider, capacitor decoder, parallel/series. | `case` (interactive), `case resistor`, `case decode`, etc. |
| **Wisdom & Spirituality** | Tao Te Ching, Bible verses, Buddhist sutras, Zen koans, Stoic quotes, Buddha quotes. | `tao`, `bible`, `verse`, `sutra`, `koan`, `stoic`, `buddha`, `wisdom` |
| **Media Playback** | YouTube video/playlist/tv embedding, direct audio streaming, curated radio stations, live TV feeds (NASA, ISS, Lofi, Gumball). | `play youtube`, `play audio`, `radio [channel]`, `tv [channel]`, `stop` |
| **Akashic Cipher Suite** | Base64 encode/decode, Caesar shift (with digit wrap), Binary/Hex streams, Vigenère cipher, Atbash mirror, AES‑256‑GCM vault with handshake password. | `encode`, `decode`, `shift`, `kryptos`, `vigenere`, `mirror`, `vault`, `handshake` |
| **Steganography & Tag Store** | Hide secret messages inside normal text via zero‑width characters; permanent private tag dictionary. | `stegano hide/reveal`, `tag set/get/view/clear` |
| **Kali Pentest Suite** | Real SHA‑256 hashing, simulated port scans, brute‑force cracking, payload injection, SSH keygen, Kali dragon banner. | `kali hash/scan/crack/inject/genkey/banner` |
| **Fun & Utility** | Riddles with reveal, dad jokes, random facts, QR codes, anime top 10, poetry, cowsay, coinflip, 8‑ball, rainbow text. | `joke`, `riddle`, `fact`, `qr`, `anime`, `poem`, `cowsay` |
| **Visual Effects** | Glitch matrix, terminal scroll bounce, animated fake hacking, React build simulator, text rotation scrambler. | `matrix`, `scroll`, `hack`, `react`, `rotate` |
| **Timers & Diagnostics** | Countdown with Morse beeps, network ping (real), system monitor (`htop`), spinner animation. | `timer`, `ping`, `htop`, `spinner`/`stopspinner` |
| **ASCII Art Gallery** | 5+ cyber‑mystical ASCII pieces: J_OS box, meditating monk, Debian swirl, Arch Linux, Kali dragon, Akashic emblem. Selectable by index. | `ascii`, `kali arch` |
| **Factory Reset** | `nuke` command clears all local data, stops animations, and resets terminal to Zero‑Point. | `nuke` |
| **UI & Mobile Polish** | Compressed terminal output for small screens, fixed ASCII wrapping, login splash responsive font, fullscreen support, `cipher` reference manual. | Automatic |

### Added
- Full terminal command runner with 40+ commands.
- Cipher suite and steganography.
- RPG mode and Kali pentest suite.
- Media playback and radio streams.

### Fixed
- Mobile responsiveness and font scaling.
- Cistercian date row alignment.

---

- *Version 4.0 makes J_OS a fast persistent information retrieval and intelligence gathering tool, a personal cipher lab, and an ambient workspace companion, all accessible from a single CLI.* 


## version 3.0 Change Log(CyberAkashicMystic) (April 2026)
| Date | Change |
|------|--------|
| 2026‑04‑11 | Added Cyber‑Fetch terminal with JOHAN_OS ASCII + maple leaf |
| 2026‑04‑11 | Added ` ` keyboard shortcuts to toggle System Info panel |
| 2026‑04‑11 | Made terminal bulletproof with try/catch and fallbacks |
| 2026‑04‑11 | Fixed mobile overflow – horizontal scrolling or size reduction |
| 2026‑04‑10 | Added Hide Controls button (top‑left) |
| 2026‑04‑10 | Improved sticky footer and removed double scrollbars |
| 2026‑04‑09 | Added responsive Cistercian clock sizes |
| 2026‑04‑08 | Integrated rainbow colours for Cistercian numerals | 
| 2026‑05‑23 | **Remote Viewing Commands** – `remoteview` (full text extraction), `grabimg` (image thumbnails), `fetchpage` (rich metadata), `portal` (interactive iframe embed) – inspired by cyberpunk OSINT fiction and CIA's Project stargate, use `api.allorigins.win` to bypass cross‑origin restrictions |
| 2026‑05‑15 | **IPTV Enhancements** – Added ability to stream IPTV channels .|

---

## 📜 Version 2.1 Change Log(Aesthetics) (March 2026)

The "Elite Update" focuses on UI symmetry, stealth interactions, and advanced state management.

| Feature | Description | Interaction |
| :--- | :--- | :--- |
| **Clock Style Toggle** | Cycle between classic analog, glass analog, and digital. | `💎 STYLE` Button or `[Z]` |
| **Clean View Toggle** | Three states: all visible, text hidden, images+text hidden. | `🖥️ CLEAN VIEW` Button    |
| **Space Preservation** | Images fade out (opacity 0) instead of `display: none` – layout never shifts. | Automatic |
| **Independent Mode** | Background cycles on a separate 30s timer from the gallery. | `🖼️ BG: SYNCED` Button |
| **Stealth Freeze** | "Ghost UI" locks the background without extra buttons. | `Double‑Click` or `[B]` |
| **Mechanical Sound 2.0** | Web Audio API generated ticks with percussive envelopes. | `playTick()` Function |
| **Pyramid UI Layout** | Re‑architected 2x2 Control Deck for visual balance. | `.controls` Flexbox |
| **Instant Mute** | One‑touch audio kill with volume memory. | `🔊` Icon Click |
| **Ambient Landing** | Site starts with deep charcoal `#121214` solid background. | Automatic on Load |

---

## version 1.0 Change Log(GENESIS)

Built a minimalistic simple analog clock

---

For a full detailed changelog with all changes, see the [CHANGELOG](https://github.com/JinKaneki/EliteGDX/CHANGELOG.md) for a complete version history.