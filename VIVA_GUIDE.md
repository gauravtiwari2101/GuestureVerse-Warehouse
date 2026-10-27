# Viva: GestureVerse Smart Warehouse

## Intro (45 seconds)
Our project is a gesture-controlled 3D smart warehouse simulator for teaching package sorting using Computer Graphics. The user controls a virtual gripper with a mouse or webcam-tracked hand gestures, picks packages from a conveyor, and places them in category-specific bins. The project shows 3D modelling, translation, rotation, perspective projection, lighting, interactive object picking, and real-time animation. It is an educational simulation, not a physical warehouse controller.

## Likely questions
1. What is Computer Graphics? — Generating and manipulating visual representations on a computer.
2. Why a warehouse? — It turns transformations and interaction into a practical pick-and-place task.
3. What is Three.js? — A JavaScript library that simplifies WebGL 3D rendering.
4. What is WebGL? — A browser API for GPU-accelerated graphics.
5. What is translation? — Changing position by a displacement vector (dx,dy,dz).
6. What is rotation? — Turning an object around an axis using angles/matrices.
7. What is scaling? — Changing object dimensions using scale factors.
8. What is perspective projection? — Mapping 3D to 2D with distant objects appearing smaller.
9. What is a camera? — A virtual viewpoint defining projection and scene view.
10. What is raycasting? — Casting a ray from the camera through the pointer to intersect 3D objects.
11. What is a scene graph? — A hierarchy of objects with local and global transforms.
12. What is an animation loop? — Repeatedly updating objects and rendering frames, typically using requestAnimationFrame.
13. What is interpolation? — Estimating values between positions; lerp makes gripper movement smooth.
14. What are lights used for? — Showing surface shape, depth, and material response.
15. How is collision checked? — The demo checks coordinate proximity to destination bin centers.
16. How is hand tracking done? — MediaPipe Hand Landmarker estimates 21 hand landmarks from webcam frames.
17. How does pinch work? — Distance between thumb tip and index tip below a threshold toggles pick/drop.
18. What if camera fails? — Mouse and keyboard are reliable alternative controls.
19. Is machine learning used? — Hand landmark detection uses a pretrained MediaPipe model; package classification itself is manual/simulated.
20. Are real warehouses controlled? — No, this is purely a virtual training simulation.
21. What is the limitation? — Simplified gripper motion and collision detection, no physical robot interface.
22. Future scope? — Inverse kinematics, physics, path planning, barcode scanning and a real robot digital twin.

## Examiner demo
1. Show warehouse and three color-coded bins.
2. Select a package, grab it, move to corresponding bin, release.
3. Show counters and accuracy.
4. Switch to top/front camera, toggle wireframe and grid.
5. Explain translations (gripper), rotations (camera, rollers), raycasting (click), and projection.
6. Optionally enable hand tracking and show pinch control.
