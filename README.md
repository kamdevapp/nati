# Nati 🎶

**Your music, your cloud.** A music player with your own home cloud – for you and your whole family,
at home, on the go, on every device.

Your music stays with you – on your computer or NAS – not on someone else's servers.
No ads, no subscription, no tracking.

*[🇵🇱 Po polsku niżej](#-po-polsku)*

## Features
- 👨‍👩‍👧 **For the whole family** – everyone has their own account, playlists, favourites and listening history
- 📱 **Always with you** – listen at home and away, and save favourites on your device for offline trips
- 🔒 **Your data stays with you** – library, accounts and playlists live on your own server
- 🎤 **Listening made enjoyable** – karaoke lyrics, equalizer and effects, skins, TV mode and full-screen visuals

## Download
Packages are in **[Releases](https://github.com/kamdevapp/nati/releases/latest)**:

| System | Package | |
|---|---|---|
| Linux (x86-64) | `Nati-<version>-x86_64.AppImage` | ✅ available |
| Windows 10 / 11 (x64) | `Nati-<version>-windows-x64-setup.exe` (or `…-portable.zip`) | ✅ available |
| Android, Android TV / Google TV | APK | later |
| macOS | app | later |
| iOS / iPadOS | App Store | later |

**Linux:** download the AppImage, make it executable and run it (no installation, works on most
distributions from Ubuntu 22.04 / Debian 12 / Fedora 38 on):
```bash
chmod +x Nati-*-x86_64.AppImage && ./Nati-*-x86_64.AppImage
```

**Windows:** download the installer and run it. Windows may warn “Windows protected your PC” (Nati is not
signed with a paid certificate yet) – click *More info* → *Run anyway*. On monitors with a high refresh rate
Nati limits itself to 60 frames per second by default (*Compatibility mode* in Settings → Appearance).

## Your cloud
Nati plays from **Nati Cloud** – your own music server. On the first start the app offers:
- **Cloud on this computer** – Nati sets it up here for you, no Docker, no configuration. It keeps
  running when the window is closed, so everyone at home can listen on their devices.
- **Connect to a cloud** – a cloud on your home server, NAS or Raspberry Pi. Install it with
  `git clone https://github.com/kamdevapp/nati-cloud && cd nati-cloud && ./chmura/install.sh`
  – see **[kamdevapp/nati-cloud](https://github.com/kamdevapp/nati-cloud)** (open source, GPL-3.0).

## Bugs and ideas
Something doesn't work or something's missing? Report it in **[Issues](https://github.com/kamdevapp/nati/issues/new/choose)**
(bug or idea – the form guides you). Questions, ideas to discuss and polls on what comes next:
**[Discussions](https://github.com/kamdevapp/nati/discussions)**.

## Support Nati
Nati is free and will stay that way. If you find it useful, you can buy the author a coffee ☕

- Ko-fi (card, Apple Pay, Google Pay – worldwide): https://ko-fi.com/kamdevapp
- BuyCoffee.to (BLIK, bank transfer – Poland): https://buycoffee.to/kamdevapp

---

## 🇵🇱 Po polsku

**Twoja muzyka, Twoja chmura.** Odtwarzacz muzyki z własną, domową chmurą – dla Ciebie i całej rodziny,
w domu, w drodze, na każdym urządzeniu.

Muzyka leży u Ciebie – na komputerze albo NAS-ie – a nie na cudzych serwerach.
Bez reklam, bez abonamentu, bez śledzenia.

### Co potrafi
- 👨‍👩‍👧 **Dla całej rodziny** – każdy domownik ma swoje konto, playlisty, ulubione i historię słuchania
- 📱 **Wszędzie z Tobą** – słuchaj w domu i poza nim, a ulubione zapisz na urządzeniu na drogę bez internetu
- 🔒 **Twoje dane zostają u Ciebie** – biblioteka, konta i playlisty są na Twoim serwerze
- 🎤 **Słuchanie z przyjemnością** – teksty z karaoke, korektor i efekty, skórki, tryb TV i pełnoekranowe tła

### Pobierz
Paczki są w zakładce **[Releases](https://github.com/kamdevapp/nati/releases/latest)**. Dziś: **Linux**
(`Nati-<wersja>-x86_64.AppImage` – pobierz, `chmod +x` i uruchom, bez instalacji) i **Windows 10 / 11**
(`Nati-<wersja>-windows-x64-setup.exe` – jeśli Windows pokaże „System Windows ochronił ten komputer”,
kliknij „Więcej informacji” → „Uruchom mimo to”). Android, macOS i iOS / iPadOS – później.

### Twoja chmura
Nati gra z **Nati Cloud** – Twojego serwera muzyki. Przy pierwszym uruchomieniu wybierasz:
- **Chmura na tym komputerze** – Nati postawi ją u Ciebie sama, bez Dockera i konfiguracji; działa też
  przy zamkniętym oknie, więc domownicy słuchają na swoich urządzeniach,
- **Połącz z chmurą** – chmura na serwerze domowym, NAS-ie albo Raspberry Pi:
  `git clone https://github.com/kamdevapp/nati-cloud && cd nati-cloud && ./chmura/instaluj.sh`
  – szczegóły w **[kamdevapp/nati-cloud](https://github.com/kamdevapp/nati-cloud)** (open source, GPL-3.0).

### Błędy i pomysły
Coś nie działa albo czegoś brakuje? Zgłoś to w zakładce **[Issues](https://github.com/kamdevapp/nati/issues/new/choose)**
(błąd albo pomysł – formularz poprowadzi Cię krok po kroku). Pytania, pomysły do omówienia i ankiety o tym,
co dalej: **[Discussions](https://github.com/kamdevapp/nati/discussions)**.

### Wesprzyj Nati
Nati jest darmowe i takie zostanie. Jeśli Ci się przydaje, możesz postawić twórcy kawę ☕

- BuyCoffee.to (BLIK, przelew – z Polski): https://buycoffee.to/kamdevapp
- Ko-fi (karta, Apple Pay, Google Pay – z całego świata): https://ko-fi.com/kamdevapp
