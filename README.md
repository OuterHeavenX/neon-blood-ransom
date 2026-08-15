# Neon Blood Ransom

A complete single-file gothic beat-’em-up for desktop and mobile. Travel through moonlit towns, cottages, woods, and cemeteries as a young vampire Night Warden. Recruit allies, learn Blood Arts, and shatter the Corrupted Signal.

**Blood Moon Beta** adds interactive combat training, a completion codex, distinctive ruler attacks and arenas, retuned progression, expanded ambient audio, and a full mobile accessibility suite.

**Nightfall Expansion** opens The Last Lantern tavern with bounties, branching decisions, rumors, and party selection. It also adds elite encounters, randomized relic rarities, castle traps and Blood Keys, a castle shortcut, richer combat animation, automatic controller support, remappable action keys, and portable save runes.

**Pixel Control Update** rebuilds heroes, companions, and enemies as crisp multi-layer pixel sprites. Mobile play is landscape-only and uses a floating analog joystick: touch anywhere on the left side to summon it, drag in any direction for continuous 360-degree movement, and release to hide it.

**True Sprite Rebuild** replaces the hand-cut Vesper atlases with one aligned master sprite sheet. The new sheet uses exact 8-by-6 cells for idle, walk, run, punch, kick, jump, and Blood Art, with transparent padding and a consistent anchor so animation frames do not chop or resize.

Movement is analog on mobile: a partial joystick tilt walks and a full tilt runs. Keyboard players hold **Shift** while moving to run.

## Play

Open `index.html` in any modern browser. No installation, server, build step, or external assets are required.

### Controls

- Move: WASD or Arrow keys
- Attack/combo: Z (third strike kicks or throws)
- Uppercut: Up + Z after learning Grave Uppercut
- Sweep: Down + Z
- Block: Hold Down while standing still
- Blood Art: X; hold and release for a charged cast
- Jump: C or Space
- Jump attack: Jump, then press Z
- Dodge roll: hold Down and press Jump
- Dash: double-tap Left or Right after learning Photon Rush
- Menu/status: Escape
- Mobile: floating 360-degree joystick on the left, plus Hit, Blood, Jump, and Menu buttons
- Controller: left stick/D-pad to move, A to attack, B to jump, X to cast, Start for menu

On iPhone, use **Share → Add to Home Screen** to launch without Safari’s address bars and get the largest play area.

The game autosaves in your browser and includes three manual save slots.

Seven combat districts feature multi-wave roads, destructible scenery, loot, healing shrines, phased bosses, quests, party recruitment, rare equipment, explorable interiors, lore, achievements, time trials, difficulty modes, New Game+, weather, and a final castle ending. Every district ruler has a unique signature attack and arena identity. Music and sound effects are generated directly in the browser without external files.

**Enterable Buildings:** Approach a marked doorway on any combat road and press Up to enter. Each district contains a themed interior with a resident, unique dialogue, permanent lore, and a one-time treasure cache. Leaving restores the street encounter exactly where it was paused.

Open **Status → Codex** to track creatures, rulers, equipment, Blood Arts, and total discovery. **Relics** lists randomized treasures, while **Controls** remaps keyboard actions and exports or imports a portable save rune. Open **System** to change difficulty; enable large text, reduced motion/flashing, high contrast, dim or left-handed controls; replay the tutorial; begin New Game+ after completing the campaign; send beta feedback; or download a self-contained offline copy.

## GitHub Pages

Suggested repository name: **neon-blood-ransom**

1. Create a repository named `neon-blood-ransom`.
2. Upload `index.html` and `README.md` to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. GitHub will provide the public game URL after deployment finishes.

All progress is stored locally per browser via `localStorage`.

## Pixel Art Assets

- `assets/vesper-vampire-concept.png` — high-resolution Vesper character concept
- `assets/vesper-animation-sheet-3x3.png` — original legacy nine-frame prototype sheet
- `assets/vesper-locomotion-atlas.png` — idle, six-frame walk, and eight-frame run cycles
- `assets/vesper-melee-atlas.png` — two punch sequences and a six-frame kick
- `assets/vesper-defense-atlas.png` — jump, hurt, block, and dodge-roll sequences
- `assets/vesper-blood-atlas.png` — Blood Art and knockdown/recovery sequences
- `assets/vesper-master-v2.png` — rebuilt 8-by-6 Vesper master sheet used by the current renderer
