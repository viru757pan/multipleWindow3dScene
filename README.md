# Multiple Window 3D Scene with Three.js

This project demonstrates how to use **Three.js** to render a 3D scene across multiple browser windows. Each window represents a part of a larger scene, and objects (like cubes) animate and reposition based on the position of each window on your screen.

## 🌐 Features

- 📦 Dynamic cube generation per open window  
- 🧠 Shared timing logic for synchronized animation  
- 🎯 Smooth interpolation when windows move  
- 🌈 Unique colors and transformations per cube  
- 🖥️ Resizable rendering canvas  
- 🪟 Tracks and manages multiple windows in real time

## 🚀 How It Works

Each window:
- Initializes a Three.js scene
- Registers itself with a central `WindowManager`
- Communicates window size and position
- Renders a cube corresponding to that window
- Animates and rotates based on global time

The main script smoothly aligns cubes with window positions, making it feel like a single 3D environment is split across multiple windows.
