# Desk Plan 3D

A to-scale 3D mockup of my desk setup for checking fit and clearances: rack, monitor arm, monitor, laptop, iPad, keyboard and the IKEA ALEX drawers.

**Live:** https://spencereholtaway.github.io/silly-desk-plan-3d/

- A single `index.html` with three.js r128 and OrbitControls. No build step.
- Works in any modern browser, with mouse or touch.
- Units are inches, with cm in the labels. The origin is the back-left corner of the desktop surface. X runs right, Y up, Z toward you.
- Tap or click an object to select it, then drag to move, lift or rotate it, or type exact values. Objects can't be scaled.
- Your layout, toggles and camera view are saved in the browser (localStorage) and restored on the next visit. "Reset layout" starts over.
- Undo / Redo buttons (Ctrl/⌘+Z, Ctrl/⌘+Shift+Z) step back through moves, rotations and toggles.
- Unverified dimensions are listed in the in-page "Assumptions & sources" panel.
