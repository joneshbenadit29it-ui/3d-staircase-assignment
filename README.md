# 🏗️ Task 8: 3D Modeling — Spiral Staircase Component

An interactive, high-fidelity 3D civil/architectural spiral staircase component built entirely with code using **Three.js (WebGL)**. This project demonstrates procedural 3D geometric modeling, custom material scripting, and dynamic studio lighting layouts within a modern developer environment.

---

## 🎨 Features & Visual Design

* **Procedural Math-Driven Geometry:** Dynamically calculates step distribution, rotation offsets, and baluster alignments using trigonometric spacing.
* **Realistic Texturing & Materials:** Implements a realistic wooden texture configuration (`MeshStandardMaterial`) for the steps alongside high-gloss metallic finishes for the support beams and handrails.
* **Studio-Grade Lighting Setup:** Utilizes a three-point lighting layout—comprising ambient illumination, a sharp cast-shadow directional key light, and a soft blue tinted rim/fill light—for premium depth and aesthetics.
* **Interactive Viewport:** Built-in `OrbitControls` enabling user-driven rotation, panning, and zooming smoothly in real-time.
* **One-Click Render Engine:** Includes a customized viewport snapshot feature that programmatically hides overlay UI components to capture and export clean, high-resolution `.png` render artifacts seamlessly.

---

## 📂 Project Structure

```text
├── index.html            # Main codebase (HTML5, CSS3 UI layout, and Three.js logic)
├── staircase_render.png  # Captured high-resolution 3D render artifact
└── README.md             # Project documentation and details
💻 Tech Stack & Tools
Core Language: HTML5, CSS3, JavaScript (ES6+)

3D Rendering Engine: Three.js (WebGL Framework via CDN)

Camera Interaction: Three.js OrbitControls

Development Environment: Visual Studio Code (VS Code)

🕹️ Live Execution Instructions
You can run this project locally instantly without installing any heavy external packages:

Clone or Download this repository to your local computer.

Open the project directory inside VS Code.

Launch the project using the Live Server extension (Click Go Live at the bottom-right corner of VS Code or right-click index.html -> Open with Live Server).

Use your mouse to interact with the model:

Left-Click + Drag: Rotate around the staircase.

Right-Click + Drag: Pan across the viewport.

Scroll Wheel: Zoom in and out.

Click the 📸 Save Rendered Image button on the screen to instantly download a brand new snapshot of the canvas viewport!


---

### 🚀 How to update it on GitHub now:
Once you save this into your `README.md` file in VS Code, push the updates to your repository by running these quick commands in your terminal:

```bash
git add README.md
git commit -m "docs: upgrade README with attractive project documentation"
git push origin main
