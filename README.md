# 2048 Tiles Visualization

An interactive visualization that displays exponentially growing tiles, extending far beyond normal JavaScript number limits using advanced mathematical notation.

## Features

- **Exponential Growth**: Watch tiles grow from 2 to numbers beyond comprehension
- **BigNum System**: Custom class handling numbers beyond JavaScript's `1.8e+308` limit
- **Omega Notation**:
  - **ω (small omega)**: Numbers beyond 10^(10^100) - First infinite ordinal
  - **Ω (large Omega)**: Numbers beyond 10^(10^200) - First uncountable ordinal
- **Array Notation**: Represents extremely large magnitudes as `{10, n}` format
- **Background Music**: Looping soundtrack that plays during simulation
- **Interactive Controls**:
  - Speed adjustment
  - Base number customization
  - Time navigation (forward/backward)
  - Quick jump buttons to different scales

## Display Format

The visualization shows numbers in three parts when reaching omega levels:

```
nΩ/ω {array} tiles
```

- **Part 1**: Omega count (e.g., `1ω` or `5Ω`)
- **Part 2**: Array notation for magnitude (e.g., `{10, 197}`)
- **Part 3**: Tile count using abbreviations (K/M/B/T/Mil/etc.)

## Test Buttons

- **90% Array**: Jump close to array notation threshold
- **Jump to ω**: Jump to small omega (10^(10^100))
- **Jump to Ω**: Jump to large Omega (10^(10^200))
- **Tier 2**: Jump to logarithmic scale
- **Ultra Speed**: Set speed to 1048576²

## Technical Implementation

- **No Recursion**: Uses iterative algorithms to prevent stack overflow
- **Log Space**: Numbers beyond `1e308` are stored as logarithms
- **Three-Tier System**:
  1. Normal numbers (< 1e308)
  2. Log space representation
  3. Power tower notation for extreme values

## Usage

1. Open `index.html` in a modern web browser
2. Check "Running!" to start the simulation
3. Use controls to adjust speed and navigate time
4. Watch the tiles grow infinitely!

## Credits

Built with mathematical concepts from set theory and large number notation systems.
