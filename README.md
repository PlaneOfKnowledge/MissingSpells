# EQMissingSpells

Missing Spells Checklist for [planeofknowledge.org](https://planeofknowledge.org/EQMissingSpells/).

Load the `<Character>_<server>-<CLASS>-MissingSpells.txt` file EverQuest writes from
`/outputfile missingspells`, then sort, search, filter by level and rank, and tick off
spells as you buy or scribe them. Checkmarks are stored per file name in a cookie with a
`localStorage` mirror, so reloading the same dump restores your progress.

Everything runs client-side — no upload, no server.

`index.html` is the whole tool — markup, styles, and script in one file. Character dumps
(`*-MissingSpells.txt`) are gitignored, so drop your own into the working copy to test against
real data.

Styling comes from the site-wide `shared.css` one directory up, so this repo is consumed as
a git submodule of the `PlaneOfKnowledge` site repo rather than served standalone.
