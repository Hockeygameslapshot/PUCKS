# Bar Down Hockey

Physics hockey in the browser. Your mouse is your stick.

Choose **2D top-down** or **3D first-person** on the start menu. Play as a skater or a goalie, in 3-on-3 games with offside, icing and penalties.

**Play:** open `index.html`, or turn on GitHub Pages for this repo.

## Controls (skater)

| Key | Action |
| --- | --- |
| W A S D | Skate (2D: screen directions · 3D: W/S forward/back, A/D turn) |
| Mouse | Stick blade. Small touches stickhandle; flick through the puck to shoot |
| Scroll | Blade tilt: open lifts the puck, closed keeps it low and hard |
| Shift | Sprint (uses stamina) |
| Space | Jump · double-tap A/D in the air to spin |
| Ctrl or X | Slide / block shots |
| Alt | Quick stop |
| R | Call for a pass |
| C | Camera |
| Esc | Pause |

## Controls (goalie)

| Key | Action |
| --- | --- |
| W A S D | Move around the crease |
| Ctrl or X | Butterfly |
| Ctrl + double-tap | Butterfly dash |
| Q / E | Stack the left / right pad |
| Mouse | Goalie stick |

Gamepads work too.

## Rules

- **Offside:** delayed. Tag up at the blue line to keep the play going.
- **Icing:** hybrid icing, so it's waved off if the shooting team would win the race to the puck.
- **Penalties:** tripping, slashing, hooking, holding, boarding, charging, interference and goaltender interference. The penalized player goes to the box and the other team gets a power play.

## Tech

It's a single HTML file with no build step. The 3D mode loads three.js r128 from cdnjs, so it needs an internet connection; the 2D mode works offline.

Made by AngryRedShark.
