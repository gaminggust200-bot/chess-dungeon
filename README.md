# Chess Dungeon

A tiny chess roguelike in a single HTML file. Draft a small army, climb the waves, and outlast the returning king.

## Play

Open `index.html` in any modern browser — there is no build step and no dependencies.

## How it works

- **Draft** three pieces (pawn, knight, bishop or rook) to join your king. The queen unlocks after wave 5.
- **Win a wave** by checkmating the enemy king or by capturing every enemy piece except the king.
- **Gold** buys permanent recruits in the shop. The armory offers one-battle cards (or 25 gold to skip), and the ruins are a gamble.
- **Difficulty** comes in four tiers. Each one unlocks when you reach wave 5 on the previous tier.
- **Challenge mode** adds a per-wave clock. Run out of time and the enemy gets reinforcements; too many timeouts and the run ends.
- **Three save slots** are kept in `localStorage`, plus your settings and difficulty progress.

## Notes

- Standard moves only: no castling or en passant, and pawns auto-promote to a queen.
- Everything — rules, AI, audio and saves — lives in one file.

## Credits

Made by [gaminggust200-bot](https://github.com/gaminggust200-bot).
