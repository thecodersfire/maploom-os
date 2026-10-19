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
