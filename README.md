# Veranstaltungs-Toolbox

**Alle Programme von Norbert Bungalski in einer App** – wie eine kleine Creative Cloud für den Mac:
zeigt alle Programme (AutoFOH, BeatLight, …), installiert sie mit einem Klick, öffnet sie und hält sie aktuell.
Neue Programme erscheinen automatisch.

Aktuelle Version: **1.0.0**

🌐 **Download-Webseite (auch für Windows & Handy):** https://bungalskin-ui.github.io/veranstaltungs-toolbox-releases/

## Herunterladen (Mac)

Auf der Seite **[Releases](../../releases/latest)** das passende Paket laden:

| Dein Mac | Datei |
|---|---|
| Mac mit M1, M2, M3 oder M4 | `Veranstaltungs-Toolbox-Mac-AppleSilicon-M1-M2-M3-M4.zip` |
| Älterer Mac (Intel) | `Veranstaltungs-Toolbox-Mac-Intel.zip` |

Welcher Mac? Apfel-Menü → „Über diesen Mac“: steht dort *Apple M…*, nimm die Apple-Silicon-Datei, bei *Intel* die Intel-Datei.
Voraussetzung: macOS 14 (Sonoma) oder neuer.

## Installieren

1. Zip entpacken, `Veranstaltungs-Toolbox` in den Ordner **Programme** ziehen.
2. Beim ersten Öffnen erscheint „nicht geöffnet“ (die App ist nicht bei Apple registriert):
   **Systemeinstellungen → Datenschutz & Sicherheit** → ganz unten **„Trotzdem öffnen“**.
   (Alternativ im Terminal: `xattr -cr "/Applications/Veranstaltungs-Toolbox.app"`)
3. Fertig. Alle Programme, die du über die Toolbox installierst, öffnen sich danach ohne Warnung.

## Updates

Die Toolbox prüft beim Start sich selbst und alle Programme. Oben erscheint **„Alle aktualisieren“**,
bei einer neuen Toolbox-Version ein Hinweis mit **„Jetzt aktualisieren“**.
