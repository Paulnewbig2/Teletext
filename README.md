# Teletext

A BetterDiscord theme in the style of teletext. Channels become pages numbered from 100, the channel title is set in double height, and everything uses the eight teletext colors and the teletext font Bedstead.

## What changes

- Channel list: every channel gets a page number starting at 100. Threads have no number.
- The selected channel is yellow on a blue bar, unread channels are white, muted channels are blue.
- The channel title is yellow and double height, like the title of a teletext page.
- Names are green, timestamps cyan, message text white.
- Messages that mention you have a magenta edge, and the mention itself is black on magenta.
- Mention counters flash on and off, as flashing text did on teletext.
- No rounded corners, no transitions, a blue message box.

## Installation

1. Download `Teletext.theme.css`.
2. In Discord, go to User Settings › BetterDiscord › Themes, open the themes folder and put the file in it.
3. Turn on Teletext in the list.

## Settings

In the `body` block near the top of the file:

| Variable | Values | Effect |
| :- | :- | :- |
| `--tt-role-colors` | `off` (default), `on` | `on` shows names in their role colors again |
| `--tt-flash` | `on` (default), `off` | `off` stops the counters from flashing |

Nothing flashes while reduced motion is on, either in Discord's accessibility settings or in your operating system.

## Based on

- The mapping of colors onto Discord's interface comes from [midnight](https://github.com/refact0r/midnight-discord) by refact0r (MIT). The theme loads midnight from refact0r.github.io at startup, and midnight loads a font from Google Fonts.
- Font: [Bedstead](https://bjh21.me.uk/bedstead/) by Ben Harris, public domain. The embedded subset covers Latin letters with accents (Latin-1 and Latin Extended-A), punctuation and the teletext mosaic characters.

## License

MIT, see [LICENSE](LICENSE).
