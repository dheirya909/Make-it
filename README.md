#  Metro Nexus
> **Make-IT Creative 2026 Submission**
> 
> *The future of smart transit. Engineered as jewellery. Wired like a pod.*

![Metro Nexus Banner](https://raw.githubusercontent.com/frogfrog21021/Make-itUfork/main/logo_wo_bg.png)

**Live Deployment:** [Visit Metro Nexus](https://metronexus.vercel.app/)

##  Concept & Creative Vision
Metro Nexus re-imagines public transit as an ambient, intelligent, and friction-less experience. No turnstiles, no tickets, no phones. By utilizing a smart wearable—**The Nexus Ring**—users seamlessly board modular, AI-routed transit pods. The ecosystem calculates fares dynamically based on exact entry/exit points and tracks congestion in real-time.

For the **Make-IT Creative** competition, we wanted to break away from traditional flat UI. Metro Nexus leverages WebGL, raw Three.js, procedural audio, and GSAP to create a sensory, cinematic interface that bridges the gap between hardware and software.

##  Key Features & Technical Highlights

*  **Immersive 3D Environments (Three.js):** Live integration of `.obj` and `.glb` files rendered in-browser with physical materials, interactive lighting, and gyroscopic mouse controls.
* **Liquid Metaball Shaders (WebGL/GLSL):** A custom WebGL shader creates a dynamic fluid cursor that morphs into different shapes depending on what UI element it hovers over (I-beams for text, hollow rings for 3D elements).
*  **Procedural UI Audio (Web Audio API):** Instead of using static `.mp3` files for button clicks, the UI generates a synthesized "metal click" with algorithmic convolution reverb in real-time, preventing audio stacking during rapid clicks.
*  **Live Interactive SVG Map:** A dynamic nodal transit map that tracks "live traffic" (high/medium/low) and prevents users from booking pods into congested zones without a warning.
*  **Firebase Backend Architecture:** Real-time wallet balances, journey histories, and live pod tracking hooked up securely via Firestore transactions.

##  The Tech Stack
* **Frontend:** HTML5, Modern CSS Variables, Vanilla JS (No heavy UI frameworks)
* **3D & Canvas:** Three.js, GLTFLoader, OBJLoader, Custom WebGL
* **Animations & Rendering:** GSAP, ScrollTrigger, Canvas API
* **Backend & Auth:** Firebase Auth, Firestore
* **Data Viz:** Chart.js, raw SVG manipulation

##  Local Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/frogfrog21021/Make-itUfork.git
