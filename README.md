# Save the King — Text RPG

A Python text-based RPG featuring class selection, turn-based combat, a branching event system, and JSON-based save/load.

## Gameplay

Choose a character class at the start, then navigate a world of combat encounters and events. Each class has distinct stats that affect viability in different situations.

| Class | HP | Attack | Style |
|-------|----|--------|-------|
| Warrior | 120 | 18 | Melee, high defense |
| Mage | 70 | 30 | Elemental, glass cannon |
| Rogue | 90 | 22 | Fast, critical-focused |

## Features

- Turn-based combat with per-class ability sets
- Branching narrative events with stat-driven outcomes
- Persistent save/load via JSON
- Modular codebase — classes, combat, events, and world logic are separated

## Run

```bash
python game.py
```

Requires Python 3.8+. No external dependencies.

## Project Structure

```
game.py          — entry point, game loop
Characters.py    — player class definitions and stat logic
core_codes.py    — combat engine, utility functions
events.py        — event definitions and branching logic
world.py         — world map and progression
ui_elements.py   — terminal display helpers
savefile.json    — persistent save data
```

## License

MIT
