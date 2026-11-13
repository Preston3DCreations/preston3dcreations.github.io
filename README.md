# Preston 3D Creations: card game rules

This repository is the website at **https://preston3dcreations.github.io**.
Each card box has a QR code pointing to its game's page, for example
`https://preston3dcreations.github.io/uno/`.

> **Never rename this repository or the GitHub account.** Every printed QR code
> depends on the address staying the same.

## Add a new game (about 1 minute)

1. Open the **`_games`** folder on github.com.
2. Open an existing game, e.g. `uno.md`, and copy its text.
3. Click **Add file → Create new file**. Name it with the address you want,
   lower case with dashes, ending in `.md`. Example: `phase-10.md` gives
   `https://preston3dcreations.github.io/phase-10/`.
4. Paste and change the values:

   ```
   ---
   name_display: Phase 10          # name shown on the page
   color: "#F7C600"                # card colour on the page
   players: 2–6                    # optional
   ages: 7+                        # optional
   publisher: Mattel               # optional
   rules: https://...              # link to the official rules
   rules_label: Mattel instruction sheet (PDF)
   ---
   A sentence or two about the game, in your own words.
   ```

5. Click **Commit changes**. The page goes live about a minute later and is added
   to the home page list automatically.

Don't paste text copied from the official rule book. Link to it instead; the
publisher owns that text.

## Fix a broken rules link

Open the game's file in `_games`, click the pencil icon, change the `rules:` line,
and commit.

## Shop links

Edit `_config.yml`, fill in the `etsy`, `makerworld`, `facebook` or `email` values,
and commit. Any left empty stay hidden.

## Add a box photo (optional)

Upload the photo to `assets/img/`, then add a line like this to the game's file:
`photo: /assets/img/uno-box.jpg`

## QR codes

The `qr` folder holds a ready-made QR code for each game (PNG and SVG). It isn't
published on the website. To make one for a new game, any QR generator works
with the game's address. Keep the address short, and test-scan the print.
