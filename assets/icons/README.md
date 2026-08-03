# site/assets/icons/

Authentic Windows 98 icons, from https://win98icons.alexmeub.com/ (Alex Meub's viewer;
the set is extracted from Windows 98 — fine for this private tool, worth a thought before
the public shell repo leans on it heavily).

**Drop a PNG named for the app id and it takes over automatically.** Anything missing falls
back to the hand-drawn pixel art in `index.html`'s `ART` table. No code change needed.

| filename        | window            | what to look for in the viewer            |
|-----------------|-------------------|-------------------------------------------|
| `surface.png`   | Surface.exe       | a document/newspaper — the daily brief     |
| `explorer.png`  | Wiki Explorer     | the open folder / Explorer icon            |
| `note.png`      | New Note          | Notepad or WordPad                         |
| `changes.png`   | Recent Changes    | clock, or the time/date control panel      |
| `search.png`    | Search            | the Find magnifier                         |
| `oracle.png`    | Oracle.exe        | something oracular — help book, agent, orb |
| `inquest.png`   | Inquest.exe       | certificate, checkmark, or a question mark |
| `why.png`       | why.exe           | imaging/photo, or anything with a heart    |
| `settings.png`  | Settings          | the display-properties monitor or gears    |
| `about.png`     | About PFC         | *(currently the purple brain — keep it?)*  |
| `flag.png`      | Start button      | *(currently the purple brain — keep it?)*  |
| `keys.png`      | logon dialog      | keys / security                            |
| `logoff.png`    | Start > Log Off   | the log-off door                           |

32×32 is the sweet spot (16×16 also works — scaling stays integer either way).
