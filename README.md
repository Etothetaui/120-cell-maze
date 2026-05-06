# The 120-Cell Maze

**The 120-Cell Maze** is a browser-based maze game built on the graph structure of the 120-cell. The game contains 600 interconnected vertex mazes, with each maze connected to neighboring mazes through exits that follow the 4-regular graph of the 120-cell.

## Play

Open the HTML file in a modern browser. No build step or server is required.

## Features

- 600 deterministic vertex mazes connected by the 120-cell graph
- Keyboard movement with arrow keys or WASD
- On-screen movement controls for mouse and touch devices
- Hold-to-move support with accelerating repeat speed
- Inset and full-screen 4D shadow map views
- Interactive map controls:
  - pause/resume rotation
  - drag to rotate
  - right-click drag or two-finger drag to pan
  - mouse wheel or pinch to zoom
  - reset map view
- Visited-only map mode
- Current cell focus mode with auto-fit
- Local progress tracking for visited vertices, fully mapped vertices, cells, and faces
- Completion stats panel showing time, transitions, revisits, efficiency, most-visited stats, last-completed stats, mapped totals, and seed
- Seeded new games
- Copy/paste save export and import with checksum validation
- Local browser save support

## Controls

| Action | Keyboard / Mouse / Touch |
|---|---|
| Move | Arrow keys, WASD, or on-screen arrows |
| Hold to move | Hold a movement key or on-screen arrow |
| Full map | `M` or Full map button |
| Visited-only map | `V` or Visited-only button |
| Current cell focus | Current cell focus button |
| Pause/resume map rotation | Pause/resume button on the map |
| Rotate map | Left-click drag or one-finger drag |
| Pan map | Right-click drag or two-finger drag |
| Zoom map | Mouse wheel, trackpad scroll, or pinch |
| Close full map | `Esc` or Close button |

## Saves and seeds

Progress is saved locally in the browser. You can also export your save as an encoded text string and import it on another device.

The maze set is generated from a numeric seed. Starting a new game with the same seed recreates the same set of mazes.

## Version

Current version: **v1.1.0**

## Development

This project is currently distributed as a single standalone HTML file containing the markup, styles, embedded 120-cell data, and game logic.

To modify it, edit the HTML file directly and open it in a browser to test.

## License

Copyright (c) 2026 Etothetaui.

This project is licensed under the GNU General Public License version 2 (GPLv2). See [`LICENSE`](LICENSE) for details.

In practical terms, people may use, share, modify, and distribute the game, including commercially, but distributed modified versions must also provide source code under the GPLv2 terms.
