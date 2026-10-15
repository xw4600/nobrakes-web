# No Brakes (Web Edition)

A browser port of the QBASIC game **NOBRAKES.BAS** (originally by Nad,
12/1/1999). A single self-contained `index.html` — no build step, no
dependencies.

## Run it

Just open `index.html` in any modern browser:

```
xdg-open index.html
```

Or serve the folder locally:

```
python3 -m http.server 8000
# then visit http://localhost:8000
```

## How to play

- Menu: **↑**/**↓** to move, **Enter** to select (Play / Instructions / About / Quit)
- **←**/**→** — dodge (you have no brakes, just keep sliding)
- **↑** or **Space** — fire
- **Enter** — pause
- **Esc** — boss key (hides the game behind a fake work screen)
- Type **point** during play — cheat: +100 score
- Score points by *passing* obstacles: Bush 1 pt, Cycle 2 pts, Car 3 pts.
  Shooting them gives no points. Level up every 100 enemies passed.
- Touch buttons appear below the canvas for mobile play.

## Gameplay faithful to the original

- Three falling enemy types (bush / cycle / car) racing down a CGA-style field.
- Player pinned at the bottom; the only defenses are dodging and blasting.
- Original menu, instructions, and about text preserved.
