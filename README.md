# 🌌 Gravity Visualizer Pro

An interactive web-based simulation of gravitational dynamics, General Relativity effects, and Minkowski spacetime diagrams. Built with vanilla JavaScript and Three.js.

![Preview](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-blue)

## ✨ Features

- **Multi-View Visualization:**
    - 3D Side View & Isometric View (WebGL/Three.js)
    - 2D Top-Down View with space-time curvature grid
    - 2D Side View with velocity vectors
    - **Minkowski Diagram** (Space-Time diagram with light cones)
- **Physics Engine:**
    - Newtonian Gravity & Relativistic corrections (toggleable)
    - Collision modes: Merge, Elastic Bounce, Fragmentation, Black Hole Collapse
    - Time Control: Play, Pause, Rewind, and Speed adjustment
- **Interactive UI:**
    - Add custom objects (Mass, Density, Position, Velocity)
    - Select objects to track them (Camera follow / Reference frame)
    - Real-time object statistics overlay
    - Dark/Light theme support
- **Data Tools:**
    - Export/Import scenes (JSON)
    - Export coordinates (CSV)
    - Save screenshots of all views

## 🚀 How to Run

Since this project uses ES Modules and `importmap` for Three.js, you cannot simply double-click `index.html`. You must run it on a local server.

### Option 1: VS Code (Recommended)
1. Open the folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html` and select **"Open with Live Server"**.

### Option 2: Python
Open a terminal in the project folder and run:
```bash
python -m http.server 8000
```
Then open http://localhost:8000 in your browser.

### Option 3: GitHub Pages
You can view the live demo directly in your browser without installing anything if the repository has GitHub Pages enabled.
## 🎮 Controls
- **Left Click** on 3D/2D view: Select an object.
- **Right Click + Drag**: Rotate 3D camera.
- **Scroll**: Zoom in/out.
- **UI Panels**: Use the top bar to control time and the side panel to manage objects.
## 🛠 Tech Stack
- **Core**: HTML5, CSS3, JavaScript (ES6+)
- **Graphics**: Three.js (via Import Map)
- **Math**: Custom Velocity Verlet Integrator
## 📜 License
This project is licensed under the MIT License.
