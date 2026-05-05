# 🌊 Game Physics — Unity Terrain & Water Environment

A Unity scene built as a final assignment for a Game Physics course (circa 2021), demonstrating environment construction, terrain sculpting, water simulation, and lighting in Unity 2020.3 LTS.

---

## 📸 Overview

This project is a 3D environment scene that showcases core Unity physics and rendering features:

- **Terrain system** — Sculpted heightmap terrain with layered materials (rock, grass/ground cover)
- **Water simulation** — High-quality reflective water using Unity's Water4Advanced system with real-time planar reflections
- **Environment lighting** — Directional light with baked lightmaps and ambient probe setup
- **Vegetation assets** — Grass and flower foliage pack integrated into the terrain
- **First-person / camera rig** — Main camera configured for scene traversal using Unity Standard Assets

---

## 🛠️ Built With

| Tool | Version |
|------|---------|
| Unity | 2020.3.21f1 (LTS) |
| Render Pipeline | Built-in (Legacy) |
| Unity Standard Assets | Camera, Characters, Environment |
| Water4Advanced | Planar reflection water |
| Grass and Flowers Pack 1 | Terrain vegetation |

---

## 🗂️ Project Structure

```
Assets/
├── Finalassignment.unity        # Main scene
├── New Terrain.asset            # Sculpted terrain data
├── NewLayer.terrainlayer        # Terrain material layer
├── Grass And Flowers Pack 1/    # Foliage assets
├── Standard Assets/             # Unity Standard Assets
│   ├── Characters/              # First-person controller
│   ├── Environment/Water/       # Water4Advanced system
│   ├── Cameras/                 # Camera rigs
│   └── ...
└── _TerrainAutoUpgrade/         # Auto-upgraded terrain layers
```

---

## 🚀 Getting Started

### Prerequisites
- Unity **2020.3.x LTS** (tested on 2020.3.21f1)
- No additional packages required — all assets are included

### Running the Project
1. Clone or download this repository
2. Open Unity Hub → **Add** → select the project folder
3. Open `Assets/Finalassignment.unity`
4. Press **Play** to run the scene

> ⚠️ Opening in a significantly newer Unity version may trigger asset migration prompts — accept them to auto-upgrade terrain layers.

---

## ✨ Features

### Terrain
Sculpted using Unity's Terrain tools with multiple painted layers:
- Ground/grass base layer
- Rock detail layer with normal maps
- Automated layer upgrade path included

### Water (Water4Advanced)
Real-time reflective water plane using Unity's built-in Water4 system:
- Planar reflection cameras (10+ reflection scene cameras)
- Preview reflection camera included
- Configurable wave parameters via standard water shaders

### Lighting
- Single directional light (sun simulation)
- Baked lightmap mode enabled
- HDR ambient sky with equator/ground gradient

---

## 📚 What I Learned

- Terrain sculpting and multi-layer painting in Unity
- Configuring Unity's Water4Advanced for real-time reflections
- Lightmap baking and light probe setup for outdoor environments
- Scene composition using Unity Standard Assets prefabs

---

## 📄 License

This project is for educational purposes. Third-party assets (Unity Standard Assets, Grass and Flowers Pack) are subject to their respective licenses.
