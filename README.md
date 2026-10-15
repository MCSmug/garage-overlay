# 🏁 Garage Overlay – kostenlose iRacing-Overlays

**Kostenlos. Ohne Abo, ohne Anmeldung, ohne Werbung, ohne Cloud.**
Das Beste aus JRT, RaceLabs, P1Doks, iOverlay und irDrive in einem Tool.

### [⬇ Garage Overlay herunterladen (Installer)](https://github.com/MCSmug/garage-overlay/releases/latest/download/GarageOverlay-Setup.exe)

Overlays **und Setup-Garage** in einem – mit Updates per Klick direkt in der App.

![Garage Overlay im Rennen](bilder/vorschau_boxenfunk.png)

---

## Installation

1. **[GarageOverlay-Setup.exe](https://github.com/MCSmug/garage-overlay/releases/latest/download/GarageOverlay-Setup.exe)** herunterladen und doppelklicken.
2. Windows fragt evtl. nach („Der Computer wurde durch Windows geschützt“) → **Weitere Informationen → Trotzdem ausführen**.
3. Installer durchklicken – keine Admin-Rechte nötig, kein .NET, kein Python. Danach steht **Garage Overlay** im Startmenü.
4. iRacing starten – die Overlays erscheinen, sobald du im Auto sitzt, im Replay oder als Zuschauer.

**Updates:** Gibt es eine neue Version, zeigt das Steuerfenster links unten **„NEUE VERSION ↓“**. Ein Klick lädt sie herunter (mit Fortschrittsbalken), installiert sie und startet neu. Deine Einstellungen und die Daten der Setup-Garage bleiben erhalten (`%APPDATA%\GarageOverlay`).

## Bedienung

| | |
|---|---|
| **Steuerfenster** | Doppelklick aufs Taskleisten-Symbol – Overlays an/aus, Spalten, Farben, Profile |
| **Verschieben** | **Strg + Umschalt + O** (oder Knopf „Overlays verschieben“), dann Overlay mit der Maus ziehen |
| **Größe** | im Verschiebe-Modus **Mausrad** – oder am **rechten/unteren Rand ziehen** (Breite / Anzahl Zeilen) |
| **Alle Overlays aus/ein** | Strg + Umschalt + H |
| **Profil wechseln** | Strg + Umschalt + P (oder automatisch je Training / Quali / Rennen) |
| **Sprit an iRacing senden** | Strg + Umschalt + F |

![Steuerfenster](bilder/vorschau_steuerfenster.png)

## Overlays

| Overlay | Was es zeigt |
|---|---|
| **Relative** | Autos vor und hinter dir mit Abstand, Lizenz + SR, iRating, BOX-Marker, Rundenabstand farbig; Warnung, wenn schnellere Autos aufschließen |
| **Standings** | Tabelle je Klasse: Abstand, Intervall, letzte/beste Runde, iRating-Prognose, gewonnene Plätze, Boxenstopps |
| **Fuel** | Reichweite in Runden, Verbrauch, Nachtankmenge, Spar-Ziel pro Runde – merkt sich den Verbrauch je Auto und Strecke |
| **Boxenstopp** | Wo du nach dem Stopp rauskommst und wer dann vor/hinter dir ist; in der Boxengasse Limiter-Warnung und Meter bis zur Box |
| **Wetter & Reifen** | Wind relativ zum Auto, Temperaturen, Nässe-Trend, Slicks/Regenreifen-Empfehlung aus dem Vergleich mit dem Feld |
| **Radar** | Autos neben dir, Warnflächen links/rechts |
| **Inputs** | Gas, Bremse, Lenkung, Gang mit Schaltblitz |
| **Delta** | ± zur Bestrunde mit Trend und Prognose |
| **Track-Map** | alle Autos in Klassenfarbe, „Geist“: wo du nach einem Boxenstopp wärst |
| **Rennflaggen & Verkehr** | gelb, blau, schwarz, Meatball …; schnellere Klassen, die dich gleich einholen |
| **Strategie / Renningenieur** | Stint- und Stopp-Planung, Hinweise im Rennen |
| **Chat** | Twitch-/YouTube-Chat (nur lesen) |

![Wetter und Reifen](bilder/vorschau_wetter_reifen.png)
![Flaggen und Verkehr](bilder/vorschau_flaggen_verkehr.png)

## Setup-Garage – deine Telemetrie-Auswertung

Die Setup-Garage ist fest eingebaut (Steuerfenster → **Setup-Garage**) und läuft komplett auf deinem PC – ohne KI, ohne Internet:

- **Wertet jede Session automatisch aus**, sobald iRacing die Telemetrie (.ibt) geschrieben hat – Training, Quali und Rennen.
- **Mein Setup:** welches Setup du gefahren bist, Bestzeit, Konstanz, saubere Runden, Spritverbrauch – und ein konkreter **nächster Schritt** (welcher Klick am Setup).
- **Vorher / Nachher:** neuer Setup-Stand gegen den alten – schneller oder langsamer, in welchen Kurven, was geändert wurde, ob der Vergleich fair ist (Temperatur, Nässe).
- **Handling-Diagnose:** Unter-/Übersteuern je Kurve (Eingang, Mitte, Ausgang) aus Lenkung, Gierrate und Gas – nur Muster, die sich wiederholen.
- **Wo die Zeit liegt:** Kurve für Kurve gegen deine beste Durchfahrt, mit Tipps („Lenkung früher öffnen“, „30 m früher Vollgas“).
- **Setup-Vergleich:** dein Setup gegen ein schnelleres – Sektoren, Speed, Gas & Bremse, Fahrlinie auf der Karte.
- **Referenzrunden:** .ibt eines schnelleren Fahrers einlegen – erscheint als Vergleich im Kurven-Coach.
- **Handy im WLAN** (optional): die Garage auf Handy oder Tablet öffnen.

Beim ersten Start fragt die Garage nach deinem iRacing-Telemetrie-Ordner (meist automatisch erkannt). Deine Daten liegen in `%APPDATA%\GarageOverlay\garage` – **Sichern = diesen Ordner kopieren.**

## Für Streamer (OBS)

Jedes Overlay gibt es als **Browserquelle mit transparentem Hintergrund**: Steuerfenster → „OBS / Stream“ → Adresse kopieren → in OBS „Quelle hinzufügen → Browser“. So geht auch „nur im Stream, nicht auf meinem Bildschirm“.

## Häufige Fragen

- **Ist das erlaubt?** Ja. Das Overlay liest nur die offizielle iRacing-Telemetrie – dieselbe Schnittstelle wie JRT, RaceLabs & Co. Es verändert nichts an iRacing.
- **Kostet das was?** Nein, und das bleibt so.
- **Hersteller-Logos:** Für die gängigen Marken sind einfarbige Symbole dabei ([simple-icons](https://simpleicons.org), CC0; die Marken gehören den Herstellern). Lieber farbige? Eigene PNGs in `%APPDATA%\GarageOverlay\logos\` legen (z. B. `Ferrari.png`) – oder eine vorhandene JRT-Installation wird automatisch genutzt.
- **Läuft es neben JRT, RaceLabs & Co.?** Ja, alle lesen dieselbe Telemetrie gleichzeitig.
- **Deinstallieren?** Windows-Einstellungen → Apps → „Garage Overlay“. Deine Daten in `%APPDATA%\GarageOverlay` bleiben dabei erhalten (bei Bedarf von Hand löschen).
- **Fehler gefunden / Wunsch?** Gern als [Issue](https://github.com/MCSmug/garage-overlay/issues) – am besten mit Bildschirmfoto und der Datei `%APPDATA%\GarageOverlay\overlay.log`.

---

### English

Free iRacing overlays plus a built-in telemetry analysis ("Setup-Garage") – no subscription, no account, no ads. Download **[GarageOverlay-Setup.exe](https://github.com/MCSmug/garage-overlay/releases/latest/download/GarageOverlay-Setup.exe)** and run it (no admin rights, no .NET or Python required, one-click updates in the app). Relative, standings, fuel, pit stop prediction, weather & tyres, radar, inputs, delta, track map, flags, OBS browser sources. The interface is currently in German.
