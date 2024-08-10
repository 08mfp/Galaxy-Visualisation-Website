# Galaxy Visualisation Website (ThreeJS)

This code is a simple solar system simulation using the `three.js` library, which demonstrates the Sun, Earth, and Moon orbiting in space. It includes textures for the planets and animates their rotation and orbits. 

## Prerequisites

Before running this program, ensure you have the following:

- A web browser that supports JavaScript and WebGL (e.g., Chrome, Firefox, Edge).
- An internet connection to load the necessary libraries and textures.

## Getting Started

### 1. Download this HTML File

1. MAke sure that the file has a `.html` extension.

### 2. Run the Program

1. Open the `.html` file in your web browser by either:
   - Double-clicking the file.
   - Dragging the file into an open browser window.

2. The program will load and display a simulation of the solar system with the Sun, Earth, Moon, and stars in the background.

## Explanation of the Code

- **HTML Structure**:
    - The `<head>` section contains metadata and links to the necessary styles.
    - The `<body>` section contains the script to initialize and animate the 3D scene.

- **JavaScript Logic**:
    - The script uses the `three.js` library to create a 3D scene with objects representing the Sun, Earth, Moon, and stars.
    - Ive implemented the texture files (and a seperate cloud layer) that wraps over the sphere to create a 3D effect.
    - `init()` initializes the scene, camera, and renderer.
    - `animate()`  updates the positions of the Earth and Moon to simulate their orbits and rotations.

- **Textures**:
    - Textures for the Sun, Earth, Moon, clouds, and stars are loaded from URLs within the script.

- **Controls**:
    - `OrbitControls` are used to allow automatic rotation of the camera, giving a dynamic view of the scene. You can drag to change view, or zoom in/out.

## Notes

- **Texture Issues**:
    - The script includes alternative URLs for the star textures in case the original one fails to load.

## Troubleshooting

- **Scene Not Displaying**:
    - Check for any console errors in your browser's developer tools (usually accessed by pressing `F12`).

- **Slow Performance**:
    - Try using a different browser or running the simulation on a device with better hardware capabilities.

## References

- [Three.js Documentation](https://threejs.org/docs/)
- [Solar System Textures](https://www.solarsystemscope.com/textures/)
