# Crazy Zombie Defense

A defense game where you protect buildings from waves of zombies. Pick a marine or a tank and control it with the mouse alone.

<p>
  <img src="docs/screenshots/screenshot-1.png" width="480" alt="Gameplay">
</p>


## How to play

Download from Releases and run it.

At the start, choose between the marine and the tank. Right click to move and left click to attack. Buildings break when your own bullets and shells hit them, so watch where you fire. Touching a zombie costs health, and the game ends when your health runs out.

Time survived, zombie count and buildings left are shown in the window title bar. Records go to the high score table, which can be cleared with a button on the start screen.


## How it works

The number of buildings left is counted with GameMaker's built in `health` value. It goes +1 when a building appears and -1 when one is destroyed, and the value is shown in the title bar as the building count. A variable meant for hit points is used as a counter.

Attack cooldown is an alarm. Clicking sets the alarm and the alarm firing creates the shot. Time survived, zombie count and building count are rewritten into the window title every frame.


## Files

| Path | Contents |
|---|---|
| `source/crazy-zombie-defense.gmk` | Original project file |
| `source/split/` | Text tree produced by GmkSplitter |
| `docs/screenshots/` | Screenshots |
| Releases | Distributed build |


## License

CC BY-NC-ND 4.0. Unmodified copies may be shared for noncommercial purposes with attribution. Modified versions and commercial use are not allowed. Bundled libraries, graphics, sounds, and maps made by other people keep their own rights. See [LICENSE](LICENSE).
