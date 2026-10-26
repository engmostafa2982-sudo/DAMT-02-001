# DAMT-02-001 — Development of the Technology City in Dammam

MODON project. File-naming code used by the contractor: **DAMT-01-002**. P6 project: **MOD3-3147**.

This repo is Layer 1 (file store) and Layer 3 (knowledge notes) of the project's second brain.

## Project basics

| Item | Value |
|---|---|
| Project ID | DAMT-02-001 (files labelled DAMT-01-002) |
| City | Dammam |
| Contractor | _to fill_ |
| Consultant | _to fill_ |
| Contract value | _to fill_ |
| Start date | 23-Dec-2025 |
| Baseline finish | 23-Feb-2027 |
| Forecast finish (update 20-10-2026) | 05-Jun-2027 |
| Active schedule | Recovery schedule REV0.00 (07-09-2026) |

## Folder structure

```
00_reference/     Contract and reference documents (BOQ, drawings, specs)
01_baseline/      Approved baseline and recovery schedules (XER)
weekly/
  YYYY-MM-DD/     One folder per data date — every file for that weekly update
notes/            AI + human weekly notes (the knowledge layer)
templates/        Templates for weekly notes
```

## Weekly upload rules

1. Create a folder in `weekly/` named with the **data date** in `YYYY-MM-DD` format (e.g. `2026-10-27`).
2. Put **all** files for that update inside it: XER, WPR Excel, PDFs, PPT, photos (`photos/` subfolder).
3. Keep the contractor's original file names — don't rename.
4. Resize photos (about 1600 px wide) before uploading; GitHub blocks files over 100 MB.
5. After upload, the weekly note goes in `notes/YYYY-MM-DD.md` using `templates/weekly-note-template.md`.
