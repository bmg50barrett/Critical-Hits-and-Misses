# Critical Tables

A one-page d100 lookup for critical hits and critical fails, made for a D&D 5.5e (2024) table and styled for Duckweed's Aeldara.

## How to use it

1. Roll a d100 when someone gets a natural 20 or a natural 1 on an attack.
2. Type the roll (1 to 100) into the box.
3. Press **Critical hit** or **Critical fail**. Enter works for a hit and Shift+Enter for a fail.

The app shows the table for that roll, its severity band, and all four rows. Read the row that matches the attack: damage type for a hit (slashing, piercing, bludgeoning, magical), or attack type for a fail (melee, ranged, natural, magical). The **Roll** button picks a random d100 if you don't have dice handy.

Open the folds at the bottom for how the tables are meant to be used and for notes on running them with the 2024 rules.

## Running it

It's a single self-contained file, `index.html`, with no build step and no dependencies. Open it in any browser, or serve it with GitHub Pages:

1. Go to **Settings > Pages** in this repo.
2. Under **Build and deployment**, set the source to **Deploy from a branch**, then pick `main` and `/ (root)`.
3. Save. The page appears at `https://bmg50barrett.github.io/Critical-Hits-and-Misses/` after a minute or two.

The table data is built into the page, so it works offline. The fonts (IM Fell English and Crimson Pro) load from Google Fonts; without a connection the page falls back to a plain serif.

## License

The critical hit and critical fail table text is Open Game Content used under the Open Game License v1.0a. The full license, the designation of Open Game Content and Product Identity, and the Section 15 copyright notice are in [OGL.md](OGL.md), and in the License fold at the bottom of the app itself.

"Duckweed's Aeldara," "Aeldara," the in-world quote, and the app's design are Product Identity and are not Open Game Content. The source code is not Open Game Content either.
