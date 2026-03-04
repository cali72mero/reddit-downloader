# CleanReddit Downloader v5.3 Beta

Empfohlener Repository-Name: `cleanreddit-downloader-v53-beta`

CleanReddit Downloader ist ein Browser-Dashboard + Bookmarklet fuer Reddit-Posts.
Es speichert erkannte Bilder, GIF/MP4-Videos und exportiert alles als ZIP.

## Features

- Reddit-Post-Erkennung im Feed und in Kommentar-Ansichten
- Bild-Erkennung mit Reddit-URL-Normalisierung (`i.redd.it`, `preview.redd.it`, `external-preview.redd.it`)
- Video/GIF-Fallback ueber Reddit-JSON (`comments/<postId>.json`, `by_id/t3_<postId>.json`)
- Einzel-Download und ZIP-Export
- User-Filter im Dashboard
- Post-Loeschen aus dem Cache (wird dann nicht in ZIP exportiert)
- Speicher-Modus: `auto`, `indexedDB`, `localStorage`
- Laufzeit-Steuerung: Start, Pause, Resume, Runtime Off, Live-Config ohne Reload

## Start

1. Ordner oeffnen: `reddit-downloader`
2. Deployment ueber GitHub Pages durchfuehren.
3. Dashboard direkt ueber die GitHub-URL aufrufen.
4. Localhost-Betrieb ist hier nicht vorgesehen.

## Nutzung

1. Dashboard im Browser oeffnen.
2. Bookmarklet-Button in die Lesezeichenleiste ziehen.
3. Reddit im selben Browser oeffnen.
4. Bookmarklet auf Reddit ausfuehren.
5. Mit `View` ins Dashboard syncen.
6. Medien einzeln oder als ZIP herunterladen.

## Browser

- Empfohlen Desktop: Chrome, Edge, Vivaldi, Opera, Firefox, Safari (macOS)
- Mobile Browser sind nur eingeschraenkt bzw. blockiert (kein voller Runtime-Modus).

## Hinweise

- `indexedDB` ist fuer grosse Mengen Posts deutlich stabiler als nur `localStorage`.
- Bei sehr grossen Exporten Render-Limit aktivieren und ZIP-Throttle anpassen.
- Nicht oeffentliche Inhalte koennen je nach Login/CORS/Rate-Limits fehlschlagen.

## Version

- Aktuell: `v5.3 beta`
- Release-Datum dieser Reddit-README: `2026-03-04`
