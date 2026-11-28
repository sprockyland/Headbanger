# 🤘 Headbangers Rock ’n’ Rente – GCBY17R (System- & Backstage-Bereich)

Willkommen im Projekt- und Verwaltungsbereich für den Mystery-Multi-Geocache **„Headbangers Rock ’n’ Rente“ (GCBY17R)** – gewidmet **Christian aka *Headbanger*** zu seinem wohlverdienten (Un)Ruhestand.

> **Hinweis zum Einstieg:**  
> Der reguläre Start für Cacher vor Ort läuft über den **normalen Zugang** (`index.html` bzw. das offizielle Geocaching-Listing).  
> Die weiteren Dateien in diesem Bereich bilden das **Backstage-, Reparatur- und Live-Radar-System** rund um den Cache.

---

## 🎸 Was ist hier los & was findest du hier?

### 1. 🚪 Cacher-Zugang & Cache-Oberfläche
* **`index.html` (Start- & Telemetrie-Weiche):**  
  Der reguläre Einstiegspunkt für Cacher (über QR-Code oder Direktaufruf). Erzeugt eine anonyme Besucher-ID (`Cacher-XXXX`), erfasst technische Eckdaten (Gerätetyp, OS, Browser, Auflösung, Netzwerk/Akku, Geo-IP) in der Firebase-Realtime-Database und leitet automatisch zur Hauptseite weiter.
* **`Headbangers_Cache.html` (Interaktives Cache-Listing):**  
  Die eigentliche Tour-Oberfläche für unterwegs – inklusive interaktiver Stations-Checklisten (`01` bis `06` / Final), Fortschrittsbalken, Vollbild-Modus, Geochecker-Link und Live-Tracking der abgeschlossenen Stationen.

### 2. 📖 Backstage-Lösungsbuch (`backstage_2.html`)
* **Variablen-Spickzettel:** Alle Lösungswerte (`A` bis `I`) auf einen Blick (`A=188`, `B=5`, `C=15`, `D=44`, `E=49`, `F=8`, `G=1`, `H=93`, `I=5`).
* **Christians Souffleur-Kasten:** Abgestufte, vorgefertigte Schubs-Tipps pro Station mit **1-Klick-Kopierfunktion** für schnelle Hilfe per Nachricht.
* **Komplette Herleitung & Hintergrundwissen:** Alle Buchstabenwerte, Peilungen, *what3words*-Koordinaten (`///trauben.auffiel.richter`), Backstage-Anekdoten sowie die schrittweise Final-Berechnung (`N 52° 30.062' E 013° 20.426'`).
* **Smart-Display-Modus:** Umschalter für „Nur Lösungen“ (blendet Hints aus) sowie „Alle auf / Alle zu“.

### 3. 🛠️ Cache Repair Center (`reparatur_2.html`)
* **Notfallbesteck für den Außeneinsatz:** Direkter Download aller Druckvorlagen und Grafik-Assets aus dem `admin`-Branch, falls vor Ort etwas beschädigt wird oder verschwindet:
  * **Station 01:** `LaternenSchild.png`
  * **Final-Dose:** `DosenBild-IN.png`, `DosenBild-OUT.png`, `FINAL-Code.png`
  * **Logbuch-Set:** `LOGBUCH-DB.jpg`, `LogBuch-Druck.jpg`, `LogBuch-Druck-blanko.jpg`
  * **Erinnerungsstücke:** `Eintrittskarte.jpg`, `URKUNDE2.png`
* Enthält außerdem einen Direktlink zum Backstage-Lösungsbuch.

### 4. 📡 Live-Radar & Statistik-Auswertung
* **`siteradar_2.html` (Echtzeit-Dashboard):**  
  Übersichtliches Live-Radar für Desktop und Smartphone. Zeigt Gesamtaktionen, Stationsfortschritt, den aktuellen Status, aufklappbare **Tour-Zeiten pro Cacher** (inkl. VIP-Erkennung für `Cacher-5PID` / Christian), Top-Aktivitäten und eine Live-Timeline.
* **`stat-headb-2026_2.html` (Admin-Statistik & Excel-Export):**  
  PIN-geschützte Detail-Konsole mit allen erfassten Einzelevents, technischen Telemetrie-Details pro Aufruf, **CSV-Export für Excel** (Windows-1252-kodiert) sowie einer 2-stufig passwortgeschützten Löschfunktion zum Bereinigen der Datenbank.

---

## 📁 Dateiübersicht

| Datei | Rolle / Bereich | Beschreibung |
| :--- | :--- | :--- |
| `index.html` | **Normaler Zugang** | Einstiegsseite mit Besucher-Tracking & automatischer Weiterleitung |
| `Headbangers_Cache.html` | **Cacher-Tour** | Hauptseite mit allen 6 Stationen, Fortschrittsanzeige & Geochecker |
| `backstage_2.html` | **Owner-Backstage** | Komplettes Lösungsbuch, Variablen-Spickzettel & Kopier-Hints |
| `reparatur_2.html` | **Wartung & Ersatzteile** | Download-Center für Schilder, Dosen-Aufkleber, Logbücher & Urkunde |
| `siteradar_2.html` | **Live-Monitoring** | Echtzeit-Radar mit Stationsstatus, Cacher-Tourzeiten & Timeline |
| `stat-headb-2026_2.html` | **Admin-Konsole** | PIN-geschützte Gesamtstatistik, Detail-Logs & CSV-Export |
