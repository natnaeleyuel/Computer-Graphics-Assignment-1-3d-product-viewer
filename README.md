# 3D Product Viewer - Interactive Chair Configurator

## 📸 Preview
![image](https://github.com/user-attachments/assets/20394067-ad1c-4e4f-8c5c-35c76e0f24b0)

An interactive web-based 3D product viewer developed as part of a computer graphics assignment. The project uses **Three.js** to render a chair model built from primitive geometries and provides a responsive interface for exploring product visualization, lighting, and user interaction in real time.

## Project Overview

This project demonstrates how computer graphics concepts can be applied in a practical product-viewing experience. It focuses on scene composition, object modeling, lighting, interaction, and camera animation, all within a browser-based 3D environment.

## Contents

- **`index.html`**: Main entry point for the application.
- **`scripts/`**: JavaScript modules for scene setup, product creation, lighting, interaction, and camera behavior.
- **`styles/`**: Styling for the UI and responsive layout.
- **`package.json`**: Project metadata and dependency configuration.
- **`package-lock.json`**: Locked dependency versions.
- **`README.md`**: Project documentation and usage guide.

## Features

- **Scene Setup**
  - Perspective camera with orbit controls
  - Responsive WebGL renderer
  - Automatic resizing on window changes

- **Product Modeling**
  - Chair model created from primitive geometries such as boxes and cylinders
  - Realistic materials using `MeshStandardMaterial`
  - Object centered at the world origin

- **Lighting System**
  - Ambient lighting for base illumination
  - Directional light with shadow support
  - Balanced light positioning for depth and clarity

- **Interactions**
  - Raycasting for selecting chair components
  - Hover and click feedback
  - Dynamic information panel for selected parts

- **Camera Animation**
  - Smooth auto-rotation around the Y-axis
  - Manual orbit control override
  - Adjustable rotation behavior

- **Bonus Features**
  - Mobile-responsive interface
  - Loading screen with spinner
  - Fullscreen mode toggle

## Technology Stack

- **Graphics Library:** Three.js
- **Languages:** JavaScript, HTML, CSS
- **Controls:** OrbitControls
- **UI Assets:** Font Awesome

## Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/natnaeleyuel/Computer-Graphics-Assignment-1-3d-product-viewer.git
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Open `index.html` in your browser, or serve the project locally if preferred.

## Interaction Guide

- **Rotate:** Left-click and drag
- **Zoom:** Mouse scroll wheel
- **Pan:** Right-click and drag
- **Select parts:** Click on chair components
- **Toggle auto-rotate:** Use the rotation control button

## Learning Outcomes

- Applied core computer graphics concepts in a browser environment
- Built interactive 3D scenes with Three.js
- Implemented raycasting for object selection
- Designed modular JavaScript for graphics features
- Improved responsive WebGL presentation techniques

## Future Enhancements

- Texture mapping support
- Multi-product switching
- AR preview mode
- Custom color picker for product customization

---

*Developed by [natnaeleyuel](https://github.com/natnaeleyuel)*
