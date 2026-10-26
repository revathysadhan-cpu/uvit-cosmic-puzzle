# UVIT: Cosmic Puzzle

A casual browser puzzle game set in simulated far-ultraviolet (FUV) and near-ultraviolet (NUV) star fields, inspired by the Ultra Violet Imaging Telescope (UVIT) on AstroSat.

Five short rounds, about five minutes per game:

| Round | Puzzle | What you do |
|---|---|---|
| A | Spot the Odd One Out | Find the source that changes dramatically between FUV and NUV |
| B | Match the Mystery | Match ringed FUV sources in a rotated NUV image with decoys |
| C | Find the Impostors | Catch hot pixels and cosmic-ray streaks hiding among real sources |
| D | Faint Source Hunt | Find faint sources, some visible in only one filter |
| E | Mystery Round | A harder mix of the above, with a hidden galaxy, AGN or variable star |

## Play

- **Online:** open the GitHub Pages link for this repository.
- **Offline:** download `index.html` and double-click it. No server, account or internet needed.

## Controls

- Click or tap a source to pick it
- `F` switch between FUV and NUV
- Arrow keys + `Space` pick a source with the keyboard (`Shift` moves faster)
- `X` swap between the two images in two-panel rounds
- `M` sound on or off

## Scoring

- +100 per correct find, with a combo multiplier up to ×3
- Round bonus +50 and a time bonus of 10 points per second left
- A wrong pick costs 25 points and 2 seconds, never the whole game
- Unlockable sky themes and marker styles are saved in your browser

## Customising

Everything is in `index.html`:

- `THEMES` and `MARKERS` hold the cosmetic unlocks
- `CARDS` holds the discovery-card text
- The puzzle generators (`genOdd`, `genMatch`, `genImpostor`, `genFaint`) sit between the `LOGIC-START` and `LOGIC-END` comments and set source counts, brightness ranges and difficulty

## Note

All fields are simulated for play. They are not real UVIT science data. Filter ranges used: FUV 1300–1800 Å, NUV 2000–3000 Å.
