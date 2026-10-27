# GestureVerse — Smart Warehouse

A browser-based 3D package-sorting simulator for a third-year Computer Graphics mini project. Built with Three.js, JavaScript, and optional MediaPipe hand tracking.

## Run
1. Extract the ZIP.
2. Open this folder in VS Code.
3. Install the Live Server extension and open `index.html` with Live Server. Or run `python -m http.server 5500` and visit http://localhost:5500.
4. Internet is needed for the Three.js CDN and MediaPipe files.
5. Click the colored box to align the gripper, press Grab / Pick, drag the cyan gripper towards the bin of the same color, then Release.
6. For webcam control, press Webcam, allow camera access, show one hand, and pinch to pick/drop. Camera tracking is experimental and may require stable lighting and internet; mouse controls are always the fallback.

## Controls
- Mouse click package: align gripper near it
- Drag cyan gripper: move in X/Z plane
- Height slider: change Y
- Grab / Pick and Release: carry and sort
- Arrow keys: move gripper; Space: pick/drop
- Drag empty scene: orbit camera; mouse wheel: zoom
- Views, grid and wireframe: graphics demonstrations

## Notes
This is a **simulation**, not an industrial robot controller. Webcam is optional. Packages are categorized using known simulated colors, not AI object recognition. A correct delivery is counted when the held package is dropped within the matching 3D bin. The scene requires browser WebGL and network access to CDN dependencies.
