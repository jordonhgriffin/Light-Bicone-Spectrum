# Light Bicone Spectrum: The Geometry of Perception

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/Version-26.2.2-blue.svg)](https://github.com/jordonhgriffin/Light-Bicone-Spectrum)

A relativistic mapping of the electromagnetic spectrum into a interactive 3D geometric manifold. This project visualizes the relationship between spacetime orientation, energy levels, and human perception.

## 🌟 Overview

The **Light Bicone Spectrum** is a real-time 3D visualization tool that maps the complexity of color and perception onto a double-conical (bicone) structure. By utilizing the vertical axis for brightness/energy, radial distance for intensity, and rotation for hue, it creates a intuitive spatial representation of how we experience light.

### 📐 Spacetime Mapping
- **Vertical Axis (Y):** Represents **Brightness/Energy**. The top apex transitions into Ultraviolet (Future/Approach), while the bottom apex descends into Infrared (Past/Recession).
- **Radial Distance (R):** Represents **Saturation and Intensity**. Objects closer to the central axis are less saturated, while those at the perimeter represent maximum spectral intensity.
- **Rotation (θ):** Represents **Hue and Variety**. Rotating around the bicone cycles through the visible spectrum.

## 🚀 Features

- **Interactive 3D Manifold:** Built with Three.js, allowing full rotation, zoom, and exploration of the spectral geometry.
- **Real-time Point Inspector:** Hover over any point on the bicone to get immediate data on its HEX code, RGB values, and wavelength (in nm).
- **Spectral Limit Mapping:** Visualizes the transition from visible light into non-visible energies like UV and IR.
- **Responsive Design:** Fully optimized for both desktop and mobile devices with custom UI controls.
- **Preset Navigation:** Quick-jump buttons for spectral landmarks (Apexes and Primary/Secondary colors).

## 🛠️ Technical Stack

- **Graphics:** [Three.js](https://threejs.org/) (WebGL)
- **Styling:** Vanilla CSS with Glassmorphism aesthetics
- **Logic:** Native JavaScript (ES6 Modules)
- **Typography:** Google Fonts (Outfit & Inter)

## 🎮 How to Use

1. **Explore:** Click and drag to rotate the bicone. Use the scroll wheel to zoom in or out.
2. **Inspect:** Move your mouse (or tap on mobile) over the surface to see real-time spectral data in the **Point Inspector**.
3. **Presets:** Use the control panel to jump to specific points like the **Top Apex (UV)** or **Bottom Apex (IR)**.
4. **Pause/Reset:** Use the playback controls to stop the default rotation or reset your camera view.

## 📦 Installation & Deployment

This is a client-side web application. To run it locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/jordonhgriffin/Light-Bicone-Spectrum.git
   ```
2. Open `index.html` in any modern web browser.

No build step or server is required, though a local development server (like `live-server` or `python -m http.server`) is recommended for the best experience.

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

**Made by [JHG](https://jordonhgriffin.github.io)**
*Version 26.2.2 | The Geometry of Perception*
