# 🤘 Headbanger Owner-Zentrale – GCBY17R

Willkommen im Backstage- und Verwaltungsbereich des Geocaches **„Headbangers Rock ’n’ Rente“ (GCBY17R)**.

> **Hinweis zum Einstieg:**  
> Der reguläre Start für Cacher vor Ort läuft wie gewohnt über den **normalen Zugang** (das offizielle Geocaching-Listing bzw. den Einstiegs-QR-Code).  
> Dieser Bereich hier ist ausschließlich als **Owner-Kommandozentrale** für Christian aka *Headbanger* gedacht.

---

## 🎸 Was ist hier los & was findest du hier?

Die **Owner-Zentrale (`owner-zentrale.html`)** bündelt alle Werkzeuge zur Überwachung, Pflege und Unterstützung des Caches an einem Ort – optimiert für Smartphone und Desktop:

### 1. 📡 Live-Radar & Datenbank-Verwaltung
* **Echtzeit-Status:** Live-Anzeige aller Stationen (1–6), Einstiege, MusicBox-Aktionen und Diplom-Aufrufe direkt aus der Firebase-Datenbank.
* **Tour-Zeiten & Cacher-Protokolle:** Detaillierte Übersicht, wer wann an welcher Station war und wie lange die Tour gedauert hat.
* **Datenpflege & Schutz:** Einzelne Test- oder Abbrecher-Einträge lassen sich gezielt aus der Statistik bereinigen (mit doppelter Sicherheitsabfrage). **Christians eigene VIP-Logs (`Cacher-5PID`) sind dauerhaft vor dem Löschen geschützt.**
* **CSV-Export:** Komplett-Export aller Telemetrie- und Verlaufsdaten für Excel.

### 2. 📖 Souffleur- & Lösungsbuch
* **Variablen-Spickzettel:** Alle gesuchten Werte (`A` bis `I`) sowie die Final-Koordinaten auf einen Blick.
* **Abgestufte Hints (Kopier-Buttons):** Vorgefertigte Schubs-Tipps pro Station zum direkten Kopieren für WhatsApp- oder Geocaching-Nachrichten, falls draußen mal jemand festhängt.
* **Komplette Herleitung:** Schritt-für-Schritt-Rechenweg bis zum Final.

### 3. 🛠️ Reparatur-Center (Ersatzteile)
* Direkter Download aller Druckvorlagen und Grafik-Assets aus dem `admin`-Branch, falls draußen ein Schild, Aufkleber oder das Logbuch erneuert werden muss:
  * `LaternenSchild.png` (Station 01)
  * `DosenBild-IN.png` & `DosenBild-OUT.png` (Final-Dose)
  * `LOGBUCH-DB.jpg`, `LogBuch-Druck.jpg` & `LogBuch-Druck-blanko.jpg`
  * `FINAL-Code.png`, `Eintrittskarte.jpg` & `URKUNDE2.png`

### 4. 🎓 Logbuch-Wall & Diplom (`hd-diplom.html`)
* Direkte Live-Ansicht der Ehrenurkunde und des digitalen Gästebuchs im **Owner-Modus (`?owner=1`)**, sodass eigene Kontrollbesuche **nicht** in der Besucher-Statistik mitgezählt werden.

### 5. 🗺️ Cache-Kopie (`cachecopie.html`)
* Vollständige Ansicht des Cache-Listings als Kopie (über den Tab oder den Schnell-Button oben rechts) – ebenfalls komplett ohne Statistik-Zähler.

---

## 📁 Dateistruktur in diesem Bereich

| Datei | Funktion |
| :--- | :--- |
| `owner-zentrale.html` | Haupt-Dashboard mit Live-Radar, Lösungsbuch, Reparatur-Center, Logbuch & Cache-Kopie |
| `cachecopie.html` | Listing-Kopie zum Nachlesen ohne Zählfunktion |
| `hd-diplom.html` | Diplom- und Gästebuch-Ansicht (mit `?owner=1` zählfrei) |
| `manifest-owner.json` | Web-App-Manifest für den Startbildschirm-Shortcut am Smartphone |
| `logo-cache.png` | Cache-Logo & App-Icon |
