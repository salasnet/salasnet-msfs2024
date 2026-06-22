# Salasnet Aiport Enhancements for Microsoft Flight Simulator 2024
SDK Source files for all of my released files at flightsim.to

Welcome to the repository for my **Microsoft Flight Simulator 2024** freeware airport and MSFS2024 enhancement projects. This repository acts as a dual-purpose archive: it contains the raw source files for SDK development alongside my final distribution builds and media assets that were uploaded to flightsim.to

You can see all of my releases on a map: [Salasnet Releases on Google Earth](https://earth.google.com/web/data=MkEKPwo9CiExQm1PbWdHMXNhVGg0NWRIakMyZ0lhTXJGZnB4ckhmNU0SFgoUMDA1MzM5NURDRjM3MjlBODhBOTcgAUICCABKCAii8r6FARAB)

---

## 📂 Project Directory

Each airport enhacement project is in a root directory, one per folder, and the final compiled zip bundles and user-facing promotional media assets used for publishing at flightsim.to are inside the `Z_flightsim_to_files` folder.

---

## 🛠️ How to Install (For Users)

If you just want to dowload these enhancements without modifying the code, please download them at Flightsim.to:

🔗 **Official Releases & Flightsim.to Profile:** [Flightsim.to Profile](https://flightsim.to/profile/salasnet/)

---

## 💻 Developer Guide

If you wish to modify, fix, contribute to these airport enhancements, or port them to MSFS 2020, you can use the SDK source files in this repository.

### Repository Architecture
* **`/[airport-code]-*/`**: Contains the SDK project environment, including the root project `.xml`, `PackageDefinitions/`, and raw placement files inside `PackageSources/`.

### How to Load a Project into the SDK
1. **Clone the repository** to your local drive or download the entire repo as a zip file.
2. Launch **Microsoft Flight Simulator 2024**.
3. Enable **Developer Mode** (*Options > General Options > Developers > Developer Mode -> ON*).
4. From the top menu bar, select **Tools > Project Editor**.
5. Click **Project > Open** and navigate to the directory of the specific airport you wish to edit (e.g., `/kism-enhancements/`).
6. Select the primary root project `.xml` file to load the asset groups into the scenery editor.

From there, you are on your own. If you are wanting to make changes, you should already be familiar with the SDK and creating and modifying airports. This just gives you my source files so you can make changes without decompiling. If you are able to backport it to MSFS 2020, please let me know at flightsim.to.

---

## ⚖️ License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license. 

You are free to copy, redistribute, and adapt these layout modifications, provided you give appropriate credit (**salasnet**) and do not exploit the data or configurations for commercial purposes. 

For full license terms, please reference the `LICENSE` file included in this repository.