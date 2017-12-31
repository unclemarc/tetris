#tetr.js

original author Simon M. Laroche, released under MIT License at https://github.com/simonlc/tetr.js

My hacks can be found at https://github.com/unclemarc/tetris

My primary driver for this was to figure out how to deploy a web based game on my OpenShift cluster in my home lab. As of December 2017, this is running on Red Hat OCP 3.6, hosted on RHV 4.1

### Default Controls: (changed by unclemarc Dec 2017, to be more like Mac Plus)

- **Rotate Left:** Z
- **Rotate Right:** K
- **Rotate 180:** Shift
- **Hold:** C
- **Hard Drop:** Space
- **Shift Left:** J
- **Shift Right:** L
- **Restart:** R

## Current mechanics and features

- Tetris Guideline compliant
    - Colors
    - Random generator, first bag never spawns Z, S, or O piece first.
    - SRS
    - Gameover by lock out or block out
    - Hold
    - Piece preview
- Game statistics like PPM, Time, etc.
- Multiple mino skins
- Stack outline
- Configurable gravity
- 60 FPS
- Fast code and drawing
- DAS and DAS delay settings
- Configurable controls
- Adjustable game size
- Ghost piece color and transparency
- Responsive design
- Preload das preservation during countdown
- Finesse faults counter.

## Planned future mechanics and features (as per Simon. I make no promises)

- Mobile design
- More game modes (ultra, etc)
- Training mode, 2step trainer, patterns, etc
- Replays
- Stats logging
- Leaderboards
- Sound effects
- T-spin and twist detection
- Custom mino skins (or at least a selection)

## TODO misc

- Help page
- Feedback button
- Include license
