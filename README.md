# Videotext

BetterDiscord-Theme im Stil von Videotext. Kanäle werden zu Seiten ab 100, der Kanaltitel steht in doppelter Höhe, alles in den acht Teletext-Farben und der Teletext-Schrift Bedstead.

## Was sich ändert

- Kanalliste: Jeder Kanal bekommt eine Seitennummer ab 100, Threads bleiben ohne Nummer.
- Gewählter Kanal gelb auf blauem Balken, ungelesene Kanäle weiß, stummgeschaltete blau.
- Kanaltitel gelb in doppelter Höhe, wie der Titel einer Videotext-Seite.
- Namen grün, Zeitstempel cyan, Nachrichtentext weiß.
- Nachrichten, die dich erwähnen, haben einen magentafarbenen Rand; die Erwähnung selbst steht schwarz auf Magenta.
- Zähler für Erwähnungen blinken wie die Blinkschrift im Videotext.
- Keine abgerundeten Ecken, keine Übergänge, Eingabefeld blau.

## Installation

1. `Videotext.theme.css` herunterladen.
2. In Discord unter Einstellungen › BetterDiscord › Themes den Themes-Ordner öffnen und die Datei hineinlegen.
3. Videotext in der Liste einschalten.

## Einstellungen

Im `body`-Block am Anfang der Datei:

| Variable | Werte | Wirkung |
| :- | :- | :- |
| `--tt-rollenfarben` | `aus` (Standard), `an` | `an` zeigt Namen wieder in ihren Rollenfarben |
| `--tt-blinken` | `an` (Standard), `aus` | `aus` stoppt das Blinken der Zähler |

Sind in Windows die Animationseffekte ausgeschaltet, blinkt nichts.

## Grundlage

- Die Zuordnung der Farben auf Discords Oberfläche kommt aus [midnight](https://github.com/refact0r/midnight-discord) von refact0r (MIT). Das Theme lädt midnight beim Start von refact0r.github.io; midnight bindet dabei eine Schrift von Google Fonts ein.
- Schrift: [Bedstead](https://bjh21.me.uk/bedstead/) von Ben Harris, gemeinfrei. Eingebettet ist eine Teilmenge mit Latein, Umlauten, Satzzeichen und Teletext-Mosaikzeichen.

## Lizenz

MIT, siehe [LICENSE](LICENSE).
