# SpaceFrogger

A free, retro-flavored frog-crossing game with modern neon graphics and a head nod to the classic arcade road-and-river hopper. Dodge space traffic, ride drifting wreckage over the void and dock in all five bays. Built phone-first with simple touch controls, and it plays great on desktop too.

**Play it in your browser:** https://nbwillcox.github.io/SpaceFrogger/

Everything is generated in code: sprites are vector-drawn on the fly, and all sound effects and music are synthesized with the Web Audio API. There are no image or audio files and no build step. A sibling of [SpaceGalaShooter](https://github.com/nbwillcox/SpaceGalaShooter), [SpaceCentiShooter](https://github.com/nbwillcox/SpaceCentiShooter), [SpaceVaderShooter](https://github.com/nbwillcox/SpaceVaderShooter), [SpaceStroids](https://github.com/nbwillcox/SpaceStroids), [SpaceCommand](https://github.com/nbwillcox/SpaceCommand), [lightCycles](https://github.com/nbwillcox/lightCycles), [SpaceRoboShooter](https://github.com/nbwillcox/SpaceRoboShooter), [SpaceBricks](https://github.com/nbwillcox/SpaceBricks) and [SpaceSidePews](https://github.com/nbwillcox/SpaceSidePews), with the same look and feel.

## Controls

| Action | Touch | Keyboard |
| --- | --- | --- |
| Hop forward | Tap anywhere | `↑` or `W` |
| Hop in any direction | Swipe that way | Arrow keys / `WASD` |
| Use the stored power-up | Tap the round POWER button | `Space` or `E` |
| Pause | Tap the pause icon | `P` or `Esc` |

Settings include a left-handed layout (power-up button on the left) and swipe sensitivity.

### Controller

Plug in a gamepad and it just works: left stick or D-pad hops, **A / X** uses the stored power-up, **Start** pauses. In menus the D-pad / left stick moves the highlight, **A** selects, **B** goes back and **Start** plays or resumes. **Settings -> Controller** has a dead-zone slider and lets you remap every button.

## Gameplay

- **Classic mode:** hop across five lanes of space traffic, past the safe median, then over five lanes of void on drifting wreckage (hulls, asteroid chunks and diving void jellies), and dock in one of the five bays at the top. Fill all five to clear the level. You have 3 lives and a 30-second timer per frog, with extra lives at 10,000 and 30,000 points.
- **Hazards:** vehicles are deadly, the void is deadly (stay on the platforms), jellies dive and resurface, platforms carry you sideways (don't get dragged off screen), a space serpent patrols the median from level 3, and a void worm lurks in empty bays from level 2.
- **Bonuses:** catch the glowing star-bug in a bay for extra points, and ride a friend frog's platform to carry them home for a bonus.
- **Power-ups** (one stored at a time): a **shield** that absorbs a hit, **slow time** that calms traffic and platforms for 6 seconds, and a **super hop** that jumps two rows.
- **Endless run:** an infinite scrolling world of roads, rivers and obstacle-dotted safe zones with one life. The void creeps up behind you, and the more distance you cover the faster it comes. Score by distance and star-bugs. Separate high scores for each mode.
- Five visual zones (asteroid belt, ion storm, neon nebula, ember rift, green drift) that change as you progress. Local top-10 high scores with arcade-style 3-letter initials, stored in your browser.

## Run locally

It is plain HTML/CSS/JS. Either open `index.html` directly, or serve the folder:

```bash
python -m http.server 8000
```

then visit http://localhost:8000 (on a phone, use your computer's local network address).

## License and attribution

Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/): free to play, share and remix **non-commercially**, as long as you give credit and **link back to this repository**: https://github.com/nbwillcox/SpaceFrogger

This is an original game inspired by classic arcade games. It uses no assets, names or code from any existing game.
