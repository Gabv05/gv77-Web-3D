# gv77-Web-3D

An interactive 3D web experience rendering custom 3D models, lighting, and camera animations directly in the browser. Built to showcase real-time WebGL graphics, procedural/keyframed animations, and responsive user controls without requiring external plugins.

---

## Key Features

- **Real-Time WebGL Rendering:** Hardware-accelerated 3D scene rendering with custom materials, PBR textures, and dynamic lighting/shadows.
- **Interactive Camera & Scene Controls:** Smooth orbit, pan, and zoom navigation alongside interactive triggers or object inspection controls.
- **Custom 3D Assets & Animations:** Integrates optimized 3D meshes (`.glb` / `.gltf`) and animated sequences exported from Cinema 4D / 3D modeling pipelines.
- **Responsive Viewport:** Automatically scales canvas aspect ratio and rendering resolution across desktop and mobile viewports.

---

## Tech Stack

- **3D Engine / Graphics:** Three.js / WebGL *(or Babylon.js / X3DOM — adjust as needed)*
- **Frontend:** HTML5, CSS3, JavaScript (ES6+) / TypeScript
- **3D Modeling & Asset Pipeline:** Cinema 4D (`glTF` / `GLB` export)
- **Bundler / Dev Server:** *(e.g., Vite / Webpack / Vanilla ES Modules)*

---

## Project Structure

```text
gv77-Web-3D/
├── index.html           # Main entry point and WebGL canvas container
├── css/                 # Viewport layout and UI overlay stylesheets
├── js/                  # Scene setup, camera controls, lighting, and animation loop
├── assets/
│   ├── models/          # Optimized .glb / .gltf 3D models
│   └── textures/        # Diffuse, normal, roughness, and environment maps
└── README.md
