# Tesla Model S - Rear Wing Aerodynamics (CFD Analysis) 🏎️🌬️

[![OpenFOAM](https://img.shields.io/badge/Simulated_with-OpenFOAM-blue.svg)](https://www.openfoam.com/)
[![CATIA](https://img.shields.io/badge/Modeled_in-CATIA-orange.svg)](https://www.3ds.com/products-services/catia/)
[![ParaView](https://img.shields.io/badge/Postprocessing-ParaView-green.svg)](https://www.paraview.org/)
[![University](https://img.shields.io/badge/Politecnico-di%20Milano-blue.svg)](https://www.polimi.it/)

Comprehensive Computational Fluid Dynamics (CFD) study investigating the aerodynamic impact of different rear wing attachment configurations on a **Tesla Model S**. 

Developed as part of the **Aerodynamics of Transport Vehicles** course at Politecnico di Milano (A.A. 2024-2025).

---

## 📌 Project Overview

The primary goal of this project is to determine how the design and placement of rear wing attachments (swan neck, standard pylons, etc.) influence the overall aerodynamic performance of the vehicle, specifically focusing on downforce generation, drag penalty, and wake structures.

> **💡 Note from the Author:** This repository marks my very first deep dive into **OpenFOAM**. While I have since honed my CFD skills and tackle much more complex setups today, this project represents my foundational steps into the world of open-source aerodynamic simulations. It serves as an academic baseline and a personal milestone! 🚀

## 📂 Repository Contents

This repository is designed to be fully reproducible. Inside you will find:

* **`Geometry/`**: Raw `.stl` files of the Tesla Model S and the different rear wing attachment geometries modeled in CATIA®.
* **`Simulations/`**: OpenFOAM setup cases. Includes all necessary dictionaries (`blockMeshDict`, `snappyHexMeshDict`, `controlDict`, etc.) to run the simulations from scratch.
* **`Docs/`**: The final academic report and presentation detailing the methodology, mesh independence studies, and results.

## 🛠️ Tech Stack & Methodology

* **3D CAD Modeling:** CATIA®
* **Meshing & Solving:** OpenFOAM® (RANS approach)
* **Post-Processing & Visualization:** ParaView

## 👨‍💻 Team "Red Bull te da alaaas" & Authors
* Francisco Javier Martín López
* Alejandro Rivera Míguez
* Alberto Rivero García
* Mikel Segovia Díaz

---

Professors: Prof. Alex Zanotti, Prof. Paolo Schito | Assistant: Ing. Stefano Negri
