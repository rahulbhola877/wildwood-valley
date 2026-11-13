# Wildwood Valley

A miniature forest valley that pops out of a pine field crate on a desk, built as a single-page Three.js scene.

**Live:** https://rahulbhola877.github.io/wildwood-valley/

## What's in the box

- A two-tier waterfall falling from a forested ridge into a clear, winding river, with a footbridge, a beaver dam and pond, and a lake with a pine-covered island
- A log cabin with a porch, chimney smoke, a dock and canoe, and a campfire
- Four seasons: spring blossom, summer green, autumn colour and falling leaves, and winter snow with frozen water and icicles
- A sun-and-moon day cycle with real-time shadows and a reflective lake
- Wildlife that keeps its own schedule: deer, a wolf pack, a mother bear and cub, foxes, beavers, herons, ducks, eagles, an owl, bats, geese, rabbits and trout
- An "In the valley now" panel listing what each animal is doing, with a Watch button that follows it
- Ambient sound synthesized live in the browser (press **Sound on**)

## Controls

- Tap the crate to open it
- Drag to look around, pinch or scroll to zoom
- Use the bar to change the time of day and the season, toggle sound and the desk lamp, start a tour or reset the view
- Tap animals, the waterfall, the campfire, the cabin or the sky to make things happen

## Running locally

It's one self-contained `index.html` (Three.js r128 loads from cdnjs). Open it in a browser, or serve the folder:

```
python3 -m http.server 8000
```

A desktop GPU draws the full scene (about 1.4 million triangles). Phones automatically get fewer trees and skip the lake reflection.
