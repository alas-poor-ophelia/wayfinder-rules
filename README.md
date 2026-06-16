# wayfinder-rules

Reference notes for the [Wayfinder](https://github.com/alas-poor-ophelia/wayfinder)
Pathfinder 1e plugin for Obsidian — one Markdown file per spell, so the sheet's
spellbook can link straight to a readable description.

Wayfinder bundles the spell **database** (the searchable table and the numbers
behind every DC and slot), but not the full spell **text** — thousands of notes
are far past what a plugin is allowed to bundle. That text lives here.

## Contents

- `spells/` — one note per spell (2,800+ files), named by spell.

More loose note sets (feats, rules) may join this repo later; that's why the
spells live under their own `spells/` folder.

## Use with Wayfinder

1. Get the notes into your vault:
   - **Clone:** `git clone https://github.com/alas-poor-ophelia/wayfinder-rules.git`
     somewhere inside your vault, or
   - **Download:** use **Code → Download ZIP** on the repo page and unzip it into
     your vault.
2. In Obsidian, open **Settings → Wayfinder → Spells folder** and point it at the
   `spells/` folder you just added.

That's it — known spells on the sheet now link to their descriptions, readable in
the sidebar. The notes are plain Markdown; trim, annotate, or replace them freely.

## License

The spell text is **Open Game Content** distributed under the Open Game License
1.0a (`OGL-1.0a.txt`). See [`NOTICE.md`](NOTICE.md) for attribution and the
Section 15 copyright notices. Product Identity is not reproduced.

This project is not published, endorsed, or approved by Paizo. "Pathfinder" is a
trademark of Paizo Inc., used here descriptively.
