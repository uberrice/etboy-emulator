# ETBoy emulator

The ETBoy simulated. Real firmware running in web assembly, in a board render.

Keys: WASD or arrows = D-pad, C or K = A, X or J = B, P = power switch, M = sound, V = 2D/3D, R = restart.
On phones a touch pad appears below the board.

## Contents

| File | |
| --- | --- |
| `index.html` | the page |
| `firmware.js`, `firmware.wasm` | the firmware, built by `tools/websim/build.sh` in pi_invaders |
| `etboy.glb` | the board, made from the KiCad STEP export by `tools/websim/step2glb.cjs` |

Generated from pi_invaders commit b08cae9. To update, rebuild
there and copy `web/emulator/{index.html,firmware.js,firmware.wasm,etboy.glb}` here.
