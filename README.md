# Level Design Demo

A first-person level design demo built in **Unreal Engine 5.6** (Blueprint-only project, originally named `SpacialCompLab`).

The main level is `Content/SpacialComp.umap`: an outdoor environment with a landscape, rocks, a lighthouse, and ambient audio (campfire, lake, ocean, cave, footsteps).

## Getting started

1. Install **Unreal Engine 5.6** (Epic Games Launcher).
2. Clone the repo:
   ```bash
   git clone https://github.com/Nivakin/Level-Design-Demo.git
   ```
3. Double-click `SpacialCompLab.uproject` (the project file keeps its original name). Unreal will regenerate `Binaries`, `Intermediate` and `Saved` on first open, which can take a few minutes while shaders compile.
4. Press **Play** in the editor. The default map is `SpacialComp`.

## Project layout

| Path | Contents |
| --- | --- |
| `Content/SpacialComp.umap` | Main demo level |
| `Content/FirstPerson/` | First-person character, blueprints and test level (`Lvl_FirstPerson`) |
| `Content/LevelPrototyping/` | Prototyping meshes, materials and interactables |
| `Content/Meshes/` | Custom meshes and materials (landscape, rocks, lighthouse glass/lamp, glow effects) |
| `Content/Audio/` | Sound waves and attenuation settings |
| `Content/Characters/Mannequins/` | Default UE mannequin assets |
| `Config/` | Project settings |

## Notes

- Packaged builds, caches and build output are not in the repo (see `.gitignore`).
- Plugins used: Modeling Tools Editor Mode, Gameplay State Tree.
