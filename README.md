# Fragments

A time-rewind puzzle platformer inspired by Braid.

## Play

Open `index.html` in your browser, or play at: https://RealMReynolds.github.io/fragments/

## Controls

| Key | Action |
|-----|--------|
| Arrow Keys / WASD | Move |
| Space | Jump |
| Hold Shift | Rewind Time |

## Mechanics

- **Time Rewind**: Hold Shift to rewind your movement. Use it to undo mistakes or solve puzzles.
- **Memory Fragments**: Collect golden fragments scattered across levels. They're **time-immune** - once collected, they stay collected even if you rewind.
- **Emotional States**: Your character changes as you collect fragments:
  - 😐 NORMAL - Balanced
  - 😢 HURT - Slower, heavier
  - 😶 NUMB - Can phase through platforms
  - 🙂 HOPEFUL - Faster, higher jumps

## Development

Built with vanilla HTML5 Canvas and JavaScript. No dependencies.

```
fragments/
├── index.html    # Complete game (single file)
├── assets/       # Sprite sheets (coming soon)
└── README.md
```

## License

MIT
