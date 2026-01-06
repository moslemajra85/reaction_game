CHRONOS | High-Fidelity Neural Response Diagnostics

CHRONOS is a sophisticated, browser-based 3D reaction diagnostic tool engineered to measure and categorize neural latency with sub-millisecond precision. Utilizing a physically-based rendering (PBR) engine via Three.js, the application provides an immersive, high-stakes environment for testing human reflexes.

🔗 Deployment

Live Environment: https://moslemajra85.github.io/reaction_game/

🚀 Key Features

PBR Optics: A glass-morphism diamond core featuring real-time refraction, thickness simulation, and chromatic highlights.

Neural Synchronization Loop: A 5-trial testing sequence designed to eliminate statistical outliers and provide an accurate performance average.

Procedural Audio: Real-time synthesis of auditory cues using the Web Audio API for zero-latency feedback.

Adaptive UX: Fully responsive architecture that maintains visual fidelity across mobile, tablet, and ultra-wide desktop displays.

🎮 Operational Protocol

Initialization: Activate the neural link by clicking the interface or pressing Space/Enter.

Calibration: The diamond enters an Indigo "Observation" state. Maintain focus.

The Strike: Upon the Emerald visual shift, trigger an immediate response.

Integrity Check: Any reaction prior to the visual shift results in a "Fractured" state, requiring a trial reset to ensure data integrity.

Data Synthesis: Following 5 successful trials, the system generates a comprehensive performance report.

🏆 Classification Hierarchy

Rank

Latency

Tier Description

GODLIKE

< 180ms

Near-instantaneous; exceeds standard human benchmarks.

ELITE

180ms - 230ms

Exceptional; consistent with high-level professional athletes.

OPTIMAL

230ms - 280ms

Standard; indicates a healthy and efficient neural pathway.

LATENCY

> 280ms

Sub-optimal; indicates significant processing delay.

🛠️ Technical Architecture

Graphics Stack

Three.js (WebGL): Implements MeshPhysicalMaterial with high transmission and clearcoat settings to simulate precious mineral properties.

Dynamic Illuminance: An orbiting PointLight system generates real-time specularity and shimmer effects.

Engineering

High-Resolution Timing: Leverages performance.now() for hardware-level timing accuracy.

Finite State Machine (FSM): Manages game logic through distinct states (IDLE, WAITING, READY, RESULT, SUMMARY) to prevent race conditions.

Audio Synthesis: Procedural oscillators generate sine and sawtooth waves, bypassing the need for heavy external assets.

📥 Installation & Local Setup

To run CHRONOS locally for testing or personal use:

Clone the Repository:

git clone [https://github.com/moslemajra85/reaction_game.git](https://github.com/moslemajra85/reaction_game.git)

Navigate to Directory:

cd reaction_game

Launch:
Open index.html in any modern web browser.
Note: No complex build steps or npm install are required as dependencies are managed via optimized CDNs.

🤝 Contributing

Contributions are welcome! If you have ideas for improving the physics engine, UI, or performance metrics:

Fork the Project.

Create your Feature Branch (git checkout -b feature/AmazingFeature).

Commit your Changes (git commit -m 'Add some AmazingFeature').

Push to the Branch (git push origin feature/AmazingFeature).

Open a Pull Request.

💾 Exporting Documentation

To save this documentation locally:

Focus on the editor panel and select all text (Ctrl+A / Cmd+A).

Copy the selection and paste it into a local editor (VS Code, Obsidian, etc.).

Save the file as README.md.
