# VOID INVADERS

> *"They came from the void. The void came with them."*

A cosmic horror arcade shooter inspired by Space Invaders, built as a single HTML file with zero dependencies.

## Play

Open `index.html` in any modern browser, or play online at:
**https://richardbowman123.github.io/void-invaders/**

## Controls

| Action | Desktop | Mobile |
|--------|---------|--------|
| Move | Arrow Keys / A,D | Touch & Drag |
| Fire | Space / Z | Tap |
| Pause | P | - |
| Mute | M | - |
| CRT Filter | C | - |

## Features

- **Procedural cosmic horror atmosphere** - parallax starfield, pulsing nebulae, progressive visual corruption
- **Evolving enemy AI** - grid march, dive-bombing, swarming behaviors that escalate with level
- **4 boss fights** - The Mothership (L5), The Leviathan (L10), The Void Eye (L15), The Architect (L20) with multi-phase destruction and unique attack patterns
- **7 weapon power-ups** - Dual Shot, Spread Shot, Rapid Fire, Plasma Beam, Seeker Missiles, Void Cannon, Chain Lightning
- **Extreme juice** - particle explosions, screen shake, slow-motion on boss hits, muzzle flash
- **Procedural audio** - all sounds generated via Web Audio API, zero audio files
- **Dynamic difficulty** - adaptive scaling based on player performance
- **6 surprise events** - Void Rift, Eclipse, Friendly Fire, Mirror, The Swarm, Reality Glitch
- **Destructible energy shields** - pixel-level erosion barriers
- **Combo scoring** - chain multiplier up to x10 with floating score popups
- **High scores** - persistent top 10 via localStorage
- **CRT filter** - optional retro scanline effect (press C)

## Technical Details

- Single `index.html` file (~1,800 lines)
- HTML5 Canvas 2D rendering at 480x720 (portrait)
- Fixed-timestep game loop at 60 FPS
- Object pooling for particles, projectiles, and effects
- Procedural vector art with glow effects (no sprites)
- Responsive scaling for any screen size
- Touch-friendly for mobile play

## License

MIT
