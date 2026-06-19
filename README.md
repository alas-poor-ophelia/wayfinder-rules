# wayfinder-rules

Reference notes for the [Wayfinder](https://github.com/alas-poor-ophelia/wayfinder)
Pathfinder 1e plugin for Obsidian — one Markdown file per spell and per Path of
War maneuver, so the sheet can link straight to a readable description.

Wayfinder bundles the spell **database** (the searchable table and the numbers
behind every DC and slot), but not the full spell **text** — thousands of notes
are far past what a plugin is allowed to bundle. That text lives here.

## Contents

- `spells/` — one note per spell (2,800+ files), named by spell.
- `maneuvers/` — one note per Path of War maneuver (400+ files), grouped into
  discipline subfolders.

More loose note sets (feats, rules) may join this repo later; that's why each
set lives under its own folder.

## Use with Wayfinder

1. Get the notes into your vault:
   - **Clone:** `git clone https://github.com/alas-poor-ophelia/wayfinder-rules.git`
     somewhere inside your vault, or
   - **Download:** use **Code → Download ZIP** on the repo page and unzip it into
     your vault.
2. In Obsidian, open **Settings → Wayfinder → Spells folder** and point it at the
   `spells/` folder you just added. For Path of War, enable it under **Settings →
   Wayfinder → Path of War** (it is off by default), then point the **Maneuvers
   folder** setting at the `maneuvers/` folder.

That's it — known spells and maneuvers on the sheet now link to their
descriptions, readable in the sidebar. The notes are plain Markdown; trim,
annotate, or replace them freely.

## License

The spell and maneuver text is **Open Game Content** distributed under the Open
Game License 1.0a (`OGL-1.0a.txt`). The spells are Paizo OGC; the maneuvers are
from Path of War and Path of War: Expanded © Dreamscarred Press. See
[`NOTICE.md`](NOTICE.md) for attribution and the Section 15 copyright notices.
Product Identity is not reproduced.

This project is not published, endorsed, or approved by Paizo or Dreamscarred
Press. "Pathfinder" is a trademark of Paizo Inc., used here descriptively.
