# Flag Studio - 3D Flag Visualizer 2026

> **Flag Studio is a Three.js-based, in-browser visualizer for cloth-simulated waving flags. Version 2026 delivers fluid wind motion, refined lighting, and export utilities for fast previews.**

[![Platform](https://img.shields.io/badge/Platform-in-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/noahhub42/flag-studio-waving-flags?style=flat-square)](https://github.com/noahhub42/flag-studio-waving-flags)

---

<p align="center">
  <a href="https://noahhub42.github.io/flag-studio-waving-flags/">
    <img src="https://img.shields.io/badge/Download-Flag%20Studio%20Latest-brightgreen?style=for-the-badge" alt="Download Flag Studio">
  </a>
</p>

> **[Direct Download - Flag Studio v2026](https://noahhub42.github.io/flag-studio-waving-flags/)**

---

[Download Latest Build](https://noahhub42.github.io/flag-studio-waving-flags/)

---

## What Flag Studio Does

Flag Studio is a browser-native 3D flag viewer powered by Three.js. It presents animated national flags inside a polished scene, with cloth-like movement, reactive wind behavior, and presentation-ready rendering that makes each flag feel like part of a live display rather than a flat asset.

The project centers on the 48 FIFA World Cup 2026 nations and is meant for quick motion previews, side-by-side visual checks, and browser-based exports. With HDRI or studio-style lighting, camera controls, and built-in export options, it serves as a lightweight web tool for flag presentation and asset inspection.

---

## Key Features

- Cloth-simulated waving flags for 48 FIFA World Cup 2026 nations
- Live wind controls with smooth transitions and gust effects
- Procedural woven fabric normal map for added surface detail
- Physically based rendering with PBR lighting
- HDRI environment support for more natural scene lighting
- Studio lighting mode for a clean presentation look
- Camera rig with depth of field for controlled framing
- Export the current render as PNG, save the source flag image, or download all flags as a ZIP

---

## Getting Started

Flag Studio runs directly in the browser, so there is no heavy setup if you just want to view the scene. You can open it from the project itself or host it on any basic static server.

To run the source locally:

1. Clone the repository:
   git clone https://github.com/noahhub42/flag-studio-waving-flags.git
2. Open the project folder:
   cd flag-studio-3d-waving-flags
3. Serve it with any static web server, then open it in your browser.

If you are using a built or hosted version, simply open the published page and start using the scene.

---

## How to Use It

1. Open Flag Studio in a modern browser.
2. Select a nation or flag to preview.
3. Adjust wind settings to change the wave motion and gust strength.
4. Switch between HDRI and studio environments depending on the look you want.
5. Use the camera rig and depth of field to refine the composition.
6. Export the current render as PNG when you want a still image.
7. Download the source flag image or export the full set as a ZIP when needed.

---

## Configuration Notes

Most controls live in the interface instead of a dedicated config file. The UI generally covers wind behavior, environment choice, camera framing, and export actions.

If you build on top of the project, keep browser-facing options in the app layer so they stay easy to tweak during preview and rendering. Asset locations and build settings can be organized through the repository layout or the hosting environment as required.

---

## Requirements

- A modern in-browser environment
- Support for Three.js-based WebGL rendering
- Enough local storage or download space for exported PNG and ZIP files
- A current browser with support for canvas textures and common web graphics features

---

## FAQ

**How do I get started?**  
Open the project in a browser or publish it as a static site, then pick a flag and begin tuning the scene.

**Can the visual style be adjusted?**  
Yes. Wind, lighting environment, camera framing, and focus-related controls are all part of the workflow.

**Where do exported files go?**  
Exports are delivered through the browser, so the final location depends on your browser's download settings and folder choice.

**Why might the preview look different on another device?**  
Rendering can differ depending on browser, GPU, and display settings. If needed, try another browser or tweak the scene controls.

**How do I update the project?**  
Swap in the latest repository contents locally or redeploy the newest build if the project is hosted.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
