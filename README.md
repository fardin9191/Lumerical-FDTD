# Lumerical-FDTD


###  High-Sensitivity Terahertz Metamaterial Sensor

This repository contains simulation codes and scripts developed during my undergraduate thesis, **“High Sensitivity Terahertz Metamaterial Sensor for Trace Pesticide Detection.”** The project focused on the design, simulation, and optimization of a metamaterial-based sensor in the **THz frequency region** using **Lumerical FDTD**.

#### 🔹 Key Features of the Work

* **Initial DRU Metastructure Design**

  * Developed a baseline Lumerical FDTD script to construct a **Double Ring Unit (DRU)** metastructure.
  * Performed **parametric sweeps** of structural thickness to identify configurations with maximum absorption.

* **Material Modeling in the THz Range**

  * Implemented **custom material models** by defining complex refractive indices in the terahertz region, which were not available in the default FDTD library.
  * Validated optical constants and integrated them into the simulation workflow.

* **Advanced Structural Modifications & Feature Enhancements**

  * Iteratively modified and optimized the metastructure to improve sensor performance.
  * Explored **5–8 different design parameters** (e.g., ring dimensions, periodicity, material variations).
  * Implemented multiple feature updates to achieve higher sensitivity.
 
 **Introduction of Pesticide Layer (Target Analyte)**
 Simulated the effect of trace pesticide residues in wheat flour by introducing a thin analyte layer on top of the metastructure. Used the Maxwell–Garnett effective medium model to represent the pesticide–flour mixture’s dielectric properties.

* **Data Handling & Post-Processing**

  * Post-processed results for absorption spectra, resonance frequency shifts, and sensitivity evaluation.


**Note::::**

The repository contains **partial code** recovered from my personal drive. A significant portion of the work (structural iterations, advanced parametric studies, and additional simulation files) was conducted on my university’s server.

