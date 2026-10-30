# HDD Failure & Forensic Recovery Lab

An interactive teaching simulation for a Digital Forensics presentation on:

1. Hard disk drive failure, physical vs logical, and data recovery methods
2. Accreditation of digital forensic laboratories (ISO/IEC 17025)

It is a single self-contained `index.html` file with no external dependencies, so it works offline.

## Sections

| Key | Section | What it shows |
|-----|---------|---------------|
| 1 | Anatomy | The main parts of a hard drive and what each one does |
| 2 | Failures | Six failure scenarios: head crash, burnt circuit board, bad sectors, deleted files, quick format, ransomware |
| 3 | Recovery | A: recovering deleted and formatted files (file table vs carving, checked with SHA-256). B: imaging a failing drive with `dd` vs `ddrescue` |
| 4 | Accreditation | Accreditation vs certification, the four ISO standards, ISO/IEC 17025 requirements, the application procedure and a readiness check |

## Controls

- **Next:** right arrow, Space, Page Down or a presentation clicker
- **Back:** left arrow or Page Up
- **Sections:** keys 1 to 4

## Running it

Open `index.html` in any modern browser, or serve the folder from a local web server (for example XAMPP at `http://localhost/lab/`).

## Note

This is a simplified teaching model. Drive behaviour, timings and damage are simulated, and the recovery figures come from the simulation, not from real drives.
