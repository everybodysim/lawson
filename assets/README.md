# Moving Block assets

The Moving Block uses a separate sprite for each of the five original Doodle art styles. Add these files when you have the art ready:

| Game style | File |
|---|---|
| N8 | `assets/moving-block-n8.png` |
| N16 | `assets/moving-block-n16.png` |
| L | `assets/moving-block-l.png` |
| M | `assets/moving-block-m.png` |
| D | `assets/moving-block-d.png` |

**Each image:** transparent PNG, ideally 16 × 16 pixels, crisp pixel art with no smoothing. Keep the silhouette and collision shape consistent across all five styles.

Each style has its own built-in pixelated placeholder. The matching placeholder disappears automatically when its matching PNG loads; missing art for other styles continues to use its own placeholder. No code edits are required when you add these files.

The block is a 16 × 16 tile with a collision box and horizontal back-and-forth movement. Its patrol range is 48 pixels to either side of its placement point.
