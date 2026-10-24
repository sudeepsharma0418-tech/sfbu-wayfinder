# SFBU Wayfinder

A walkable 3D map of the SFBU building, so new students can find any room on their first day.

Pick a room and the map draws the route and gives you step by step directions. You can also switch to "Walk inside" and move around yourself with the arrow keys.

## What's new in v2

**Ask the guide.** New students don't know room names, they know what they need. So you can now type a question like "where can I print?" or "my login isn't working". The guide picks the right room, draws the route, and offers a "Walk me to..." button.

- Inside Claude, the guide uses AI to understand the question.
- On GitHub Pages, it uses a simple keyword search instead, since there is no AI there.

**Live walking time.** Like a maps app, the map shows how many minutes to walk, the distance, and the time you will arrive. It updates live as you walk.

These ideas came from my Week 10 SCAMPER and Week 11 AI opportunities work. Version 1 is still here as `v1.html`.

## How to use

1. Open `index.html` in a browser (or the GitHub Pages link).
2. Choose a room under **Where to?**
3. Click **Show route** or **Walk me there**.
4. Use the arrow keys or the on screen pad to walk. Drag to look around.

## How it was made

I drew the layout of the ground floor by hand from memory (`sketch.jpg`). Then I used AI (Claude) to turn my sketch into a 3D model with Three.js, plus the walking controls and the route finder.

Human part: the problem, the hand drawn layout, the features, and testing it against my sketch.
AI part: the 3D code, controls, and pathfinding.

## Notes

This is a low fidelity prototype. Ground floor only, and room sizes are approximate. 1 grid square is about 2 m.

Made for APP203 Midterm Creative Sprint at San Francisco Bay University.
