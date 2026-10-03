# Barrierefreies WebUntis (Android)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Platform: Android](https://img.shields.io/badge/Platform-Android-green.svg)](android)
[![Accessibility: TalkBack Ready](https://img.shields.io/badge/Accessibility-TalkBack%20Ready-brightgreen.svg)]()
[![F-Droid Ready](https://img.shields.io/badge/F--Droid-Ready-blue.svg)](fdroid)

**Barrierefreies WebUntis** ermöglicht blinden und sehbehinderten Schülerinnen und Schülern sowie Lehrkräften den barrierefreien Zugriff auf ihre Stundenpläne und Vertretungen. Ursprünglich entwickelt mit und für Schüler des LWL-Berufskollegs Soest.

---

## ✨ Features & Barrierefreiheit

* **TalkBack-optimierte Stundenplanansicht:** Direkte Sprachausgabe von Fach, Raum, Lehrkraft und Ausfällen ohne störende Tabellengewirre.
* **Tages- & Wochennavigation:** Schnelles Wechseln zwischen Schultagen und Wochen.
* **Vertretungsplan:** Unmittelbare Hervorhebung von Entfall, Vertretungen und Raumänderungen.
* **Offline-Caching:** Stundenpläne bleiben auch im Funkloch oder offline lesbar.
* **Barrierefreies Kontrast-Design:** Einstellbare Kontraste und große Typografie.

---

## 🛠️ Projektstruktur

* `www/`: Barrierefreie Web-Applikation
* `android/`: Natives Android-Projekt mit Capacitor HTTP Plugin
* `fastlane/metadata/android/`: Metadaten für F-Droid
* `fdroid/`: F-Droid Rezept (`de.lwl.stundenplan.yml`)

---

## 🚀 Bauen aus dem Quellcode

```bash
npm ci
npx cap sync android
cd android
./gradlew assembleRelease
```

---

## 📄 Lizenz

Dieses Projekt steht unter der [MIT-Lizenz](LICENSE).
