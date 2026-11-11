# Star Trek: Red Alert — Bridge Command

A fan-made, single-file Star Trek card battler. Play as Captain of the USS Enterprise NCC-1701 and survive three escalating enemy encounters in an authentic LCARS-style interface.

## How to play

Open `index.html` in any modern browser — no dependencies, no build step, no server required.

Each turn you receive **energy** to play cards from your hand:

- **Weapons** — direct damage (Phaser Array Strike, Photon Torpedo)
- **Science** — damage plus card draw (Targeting Scan, Long-Range Sensors)
- **Engineering** — shields, hull repair, and extra energy (Reinforce Shields, Damage Control, Emergency Power)
- **Crew** — special abilities with ship's officers (Kirk, Spock, McCoy, Uhura, Sulu, Chekov)

Shields absorb damage first and regenerate slowly each turn; hull does not, unless your doctor works a miracle.

## Enemies

1. **IKS Kronos One** (Klingon D7) — unleashes a devastating barrage every 3rd attack
2. **IRW Valdore** (Romulan Warbird) — intermittently cloaks, halving your damage until it decloaks
3. **Borg Cube** — adapts every turn (+1 armor, hull regeneration); destroy it fast

## Play in the browser (GitHub Pages)

After merging, enable Pages: **Settings → Pages → Deploy from branch → main / (root)**. The game will then be playable at `https://lukaskonias-ops.github.io/Card-game-X/`.
