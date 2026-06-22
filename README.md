# salasnet-msfs2024
SDK Source files for airport enhancements and modification for MSFS 2024

Welcome to the repository for my **Microsoft Flight Simulator 2024** freeware airport enhancement projects. This repository acts as a dual-purpose archive: it contains the raw source files for SDK development alongside my final distribution builds and media assets that were uploaded to flightsim.to

All projects here focus on refining and enhancing stock airports in Florida by utilizing the simulator's native asset library.

---

## 📂 Project Directory

Each airport enhacement project is in the root directories, one per folder, and the final compiled distribution builds inside the `Z_flightsim_to_files` folder.

---

## 🛠️ How to Install (For Users)

If you just want to dowload these enhancements without modifying the code, please download them at Flightsim.to:

🔗 **Official Releases & Flightsim.to Profile:** [Flightsim.to Profile](https://flightsim.to/profile/salasnet/)

---

## 💻 Developer Guide

If you wish to modify, fix, contribute to these airport enhancements, or port them to MSFS 2020, you can open and edit them using the MSFS 2024 Developer Mode SDK.

### Repository Architecture
* **`/[airport-code]-*/`**: Contains the active SDK project environment, including your root project `.xml`, `PackageDefinitions/`, and raw placement files inside `PackageSources/`.

* **`/Z_flightsim_to_files/`**: Contains the final compiled zip bundles and user-facing promotional media assets used for publishing at flightsim.to.

### How to Load a Project into the SDK
1. **Clone the repository** to your local drive or download the entire repo as a zip file.
2. Launch **Microsoft Flight Simulator 2024**.
3. Enable **Developer Mode** (*Options > General Options > Developers > Developer Mode -> ON*).
4. From the top menu bar, select **Tools > Project Editor**.
5. Click **Project > Open** and navigate to the directory of the specific airport you wish to edit (e.g., `/kism-enhancements/`).
6. Select the primary root project `.xml` file to load the asset groups into the scenery editor.

From there, you are on your own. If you are wanting to make changes, you should already be familiar with the SDK and creating and modifying airports. This just gives you my source files so you can make changes without decompiling.

---

## ⚖️ License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license. 

You are free to copy, redistribute, and adapt these layout modifications, provided you give appropriate credit (**salasnet**) and do not exploit the data or configurations for commercial purposes. 

For full license terms, please reference the `LICENSE` file included in this repository.