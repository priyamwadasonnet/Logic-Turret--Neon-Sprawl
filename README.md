# Logic-Turret--Neon-Sprawl 🟦🟪

**Logic-Turret--Neon-Sprawl** is a cyberpunk tactical simulation where players architect a turret's "brain" using a real-time visual logic graph. Built with vanilla JavaScript and HTML5 Canvas, it challenges players to balance mathematical trade-offs to survive 30 waves of robotic incursions.

---

## 🛠 Technical Highlights

This project was developed as a deep dive into **Visual Scripting Systems** and **Procedural Animation** without the use of external engines or frameworks.

* **Custom Logic Engine:** A recursive evaluation system that parses user-built node graphs to calculate turret telemetry (Damage, RPM, Range) in real-time.
* **2.5D Isometric Rendering:** A hybrid rendering pipeline that projects 2D world coordinates into isometric space with billboarded pixel-art sprites.
* **Procedural Visual Effects:** Dynamic lightning (Tesla), ray-casting (Laser), and physics-based particle explosions.
* **Zero-Dependency Architecture:** Optimized for web performance and rapid loading using pure Canvas API.

---

## 🕹 Mechanics

In **Logic-Turret--Neon-Sprawl**, the "UI" is the game. Players don't just upgrade stats; they build them.

1.  **Nodes:** Purchase and place mathematical operators (*Add, Multiply, Divide*) and *Value* nodes.
2.  **Wiring:** Connect outputs to inputs to create a data flow.
3.  **Telemetry:** Wire your final values into the **PWR** (Power) terminals.
4.  **Modules:** Install Weapon Archetypes to fundamentally change projectile behavior:
    * **Tesla:** Multi-target chain lightning.
    * **Laser:** High-damage piercing beam.
    * **Time:** Chrono-displacement field that slows enemies.
    * **Cannon:** High-splash artillery.

---

## 🚀 Installation & Deployment

Since this project is built with vanilla web technologies, it requires no build step.

1.  Clone the repository:
    ```bash
    git clone https://github.com/YOUR_USERNAME/logic-neon.git
    ```
2.  Open `index.html` in any modern web browser.

---
