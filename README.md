# NWN Constants

VB6 utility (project Project1) that scans `C:\temp\NWN\*.NSS` Neverwinter Nights script includes and exports numeric constants to CSV. For each `.NSS` file it writes `CONSTANTS_<file>.CSV` with columns type, name, and value, keeping uppercase `INT`/`FLOAT` constants that have a simple `=` assignment (skipping comments, functions with parentheses, and non-numeric expressions). Startup form `Form1` runs the scan on load then exits.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`NWN Constants.vbp`) | VB6 | WinForms exe | Extract NWN NSS INT/FLOAT constants to CSV |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `NWN Constants.vbp`

## Requirements

- Visual Basic 6.0 IDE
- NWN `.NSS` includes present under `C:\temp\NWN` (path hard-coded)

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/NWN Constants`.
Targets Bioware Neverwinter Nights NWScript include constants.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
