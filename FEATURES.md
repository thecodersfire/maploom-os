# Built-in features for maploom-os

Purpose: geographic information systems

1. **prepare field and mapping files** — run maploom-os-workspace. It creates ~/Documents/maploom-os-workspace/ with Field Notes, Source Data, Map Exports folders.
2. **plan field work** — run maploom-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/maploom-os-session-plans/.
3. **check data and location readiness** — run maploom-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/maploom-os-workspace features/maploom-os-plan features/maploom-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for geographic information systems:

1. **GNOME Maps** — org.gnome.Maps
2. **Zotero** — org.zotero.Zotero
3. **VSCodium** — com.vscodium.codium

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for geographic information systems:

1. **GNOME Weather** — check local weather conditions (org.gnome.Weather)
2. **darktable** — develop RAW photos (org.darktable.Darktable)
3. **GIMP** — edit raster graphics and textures (org.gimp.GIMP)
4. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
5. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
6. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
7. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
8. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
9. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
10. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
2. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
3. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
4. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
5. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
6. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
7. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
8. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
9. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
10. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
11. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
12. **QElectroTech** (org.qelectrotech.QElectroTech) — draw electrical schematics and wiring diagrams.
13. **GNOME Calculator** (org.gnome.Calculator) — perform scientific and financial calculations.
14. **Disk Usage Analyzer** (org.gnome.baobab) — find large files and manage storage.
15. **GNOME Logs** (org.gnome.Logs) — inspect logs during troubleshooting.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **Marble** (org.kde.marble) — explore maps and a virtual globe for geographic context.
2. **KGeography** (org.kde.kgeography) — practice country, capital, and map recognition.
3. **KGeoTag** (org.kde.kgeotag) — add GPS coordinates to photos from a GPX track or map.
4. **KStars** (org.kde.kstars) — plan sky observations and explore astronomy simulations.
5. **Gwenview** (org.kde.gwenview) — review image sets and make quick crop, resize, and annotation edits.
6. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
7. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
8. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
9. **Ark** (org.kde.ark) — open and create common project archive files.
10. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
11. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
12. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.
13. **Kate** (org.kde.kate) — edit configuration, code, notes, and structured project files.
14. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.
15. **Konsole** (org.kde.konsole) — run shell commands and inspect development or system tasks.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.

## Blender included in every setup

Blender (org.blender.Blender) is included in every setup for 3D modeling, animation, rendering, and video editing. Installers fetch it from Flathub; Blender’s own license and terms apply.

## Fifteen additional purpose-specific applications

The setup adds these Flathub applications for geographic information systems. Applications are fetched from Flathub by the setup script; each app keeps its own licensing and terms.

1. **Kst** (org.kde.kst) — Display and inspect scientific measurement and time-series data.
2. **LabPlot** (org.kde.labplot) — Plot and analyze data imported from spreadsheets or research files.
3. **KBibTeX** (org.kde.kbibtex) — Edit BibTeX references for academic writing.
4. **KPhotoAlbum** (org.kde.kphotoalbum) — Tag and organize large photo collections.
5. **Tellico** (org.kde.tellico) — Catalog books, media, games, and other collections.
6. **PDF Arranger** (com.github.jeromerobert.pdfarranger) — Reorder, rotate, split, and merge PDF pages.
7. **LocalSend** (org.localsend.localsend_app) — Transfer files directly between nearby devices on your local network.
8. **Joplin** (net.cozic.joplin_desktop) — Organize notes and checklists in notebooks.
9. **KBackup** (org.kde.kbackup) — Create user-selected backup archives of files and folders.
10. **Déjà Dup** (org.gnome.DejaDup) — Create user-configured file backups to a chosen destination.
11. **KRename** (org.kde.krename) — Batch rename photo, document, and project files.
12. **Skanpage** (org.kde.skanpage) — Scan and arrange multipage documents from a connected scanner.
13. **Merkuro** (org.kde.merkuro) — Organize calendars, contacts, and tasks.
14. **Kontact** (org.kde.kontact) — Organize personal email, contacts, calendars, and tasks.
15. **KMyMoney** (org.kde.kmymoney) — Track personal accounts, budgets, and expenses locally.
