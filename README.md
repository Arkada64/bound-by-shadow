# Bound by Shadow

A stealth survival game idea: a procedurally generated building (manor, hospital, slaughterhouse), an AI killer that has to actually find you, and AI survivors you can help or abandon.

## Prototype

`prototype/index.html` is a single-file browser prototype for testing whether the core loop is fun. Open it in a desktop browser (keyboard and mouse).

- Scavenge containers for keys, fuses, med-kits, batteries and firecrackers
- Restore power (generators, fuse boxes), then open an exit gate
- The killer is picked at random and hunts by sight, sound or blood, depending on which one it is
- A director nudges the killer toward survivors without telling it where they are
- Two-story maps joined by stairs, pallets you can drop in doorways, and generators that need two gas cans each
- Play in a third-person 3D view (three.js) or the original top-down 2D view; both run the same simulation
- Press `V` in game to reveal what the AI is thinking
