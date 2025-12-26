# game-dcc-asset-template
# Game DCC Asset Template (Maya → Unreal)

A **minimal, production-ready DCC pipeline template** for creating **single game assets** using **Autodesk Maya**, optimized for export to **Unreal Engine**.

## 🎯 Goals

- Keep the pipeline **clean & lightweight**
- Avoid over-engineering
- Maintain **clear structure, naming, and versioning**
- Be scalable if the asset grows later

---

## 📁 Folder Structure

```plaintext
asset_name/
├─ maya/
│   ├─ work/        # Maya working files (.ma)
│   ├─ export/      # FBX files for game engine
│   └─ cache/       # Simulation / bake cache (ignored by git)
│
├─ textures/
│   ├─ source/      # Substance Painter / Designer files
│   └─ export/      # Engine-ready textures
│
├─ reference/       # Concept, photo reference
└─ README.md        # Asset-specific notes
