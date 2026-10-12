# Mod asset guide

## Moving block

The moving block currently draws a built-in pixel-art placeholder. To replace it, add:

- `assets/moving-block.png`
- PNG with transparency
- Recommended size: **16 × 16 pixels** (the game renders it at 16 × 16)
- Style: crisp pixel art, readable outline, cool blue/steel platform colors

The game automatically uses this image when it loads successfully; otherwise the built-in pixelated placeholder stays visible. No code edits are needed when adding the PNG.

The moving block is a solid 16 × 16 tile. Its horizontal travel range is 3 tiles in either direction from where it was placed, and it reverses automatically at each end.
