# site/assets/icons/

Authentic Windows 98 icons from Alex Meub's viewer (https://win98icons.alexmeub.com/,
downloaded 2026-08-03). Extracted from Windows 98 — fine for this private tool; worth a
thought before the public shell repo leans on them heavily.

**Drop a PNG named for the app id and it takes over automatically** — no code change.
Anything missing falls back to the hand-drawn pixel art in `index.html`'s `ART` table.
Sizes stay integer-scaled at every zoom level, so both paths render pixel-crisp.

| file           | window         | source icon                  | why |
|----------------|----------------|------------------------------|-----|
| `surface.png`  | Surface.exe    | `newspaper`                  | the daily brief, literally a paper |
| `explorer.png` | Wiki Explorer  | `directory_open_file_mydocs` | open folder of documents |
| `note.png`     | New Note       | `notepad-1`                  | Notepad |
| `changes.png`  | Recent Changes | `history`                    | clock over a page |
| `search.png`   | Search         | `magnifying_glass`           | the Find lens |
| `oracle.png`   | Oracle.exe     | `help_book_big`              | purple tome, gold question mark — and it matches the wallpaper palette |
| `inquest.png`  | Inquest.exe    | `certificate_seal`           | a sealed ruling |
| `why.png`      | why.exe        | `kodak_imaging`              | a framed picture — the app *is* a picture frame |
| `settings.png` | Settings       | `display_properties-2`       | the monitor; Settings is a Display Properties pastiche |
| `keys.png`     | logon dialog   | `key_win`                    | keys for the token prompt |

**Deliberately still hand-drawn:** `about` and `flag` (the Start button) wear Andrew's
purple brain — the mark that makes this desktop his rather than a Windows reproduction —
and `logoff` keeps its pixel padlock (the set has no log-off door).
