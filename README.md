# Geometry Mesh Rendering | AlphaAlgebra Engine v3.0
### Advanced Computational Geometry & Recursive Fractal Visualization

<img width="435" height="581" alt="Screenshot 2026-04-06 9 49 06 PM" src="https://github.com/user-attachments/assets/aa2f0f9f-26e8-45d6-9f63-0ec0cd0b37b8" />

<img width="543" height="594" alt="Screenshot 2026-04-06 10 23 37 PM" src="https://github.com/user-attachments/assets/c2eb79f3-2274-4b4c-a483-e7e39cded3eb" />



## Project Ethos
**AlphaAlgebra** is a technical deep-dive into **3D spatial mathematics** and **hacker-aesthetic rendering**. This suite demonstrates how to architect complex geometric relationships—ranging from convex hull derivations to recursive volumetric fractals—within a high-performance WebGL environment.

## Technical Stack
*   **Core Engine:** `Plotly` (3D WebGL Rendering)
*   **Spatial Logic:** `SciPy.spatial` (Convex Hull & Centroid Calculation)
*   **Vector Math:** `NumPy`
*   **Deployment:** Standalone HTML/JS for cross-platform portability.

## Algorithmic Highlights
*   **Dual-Nature Inversion:** Programmatically deriving the vertices of a Dodecahedron from the centroids of an Icosahedron's faces.
*   **Recursive Menger Engine:** A fractal subdivision algorithm demonstrating recursive depth management and high-volume mesh rendering.
*   **Volumetric "Cyber-Glow":** Multi-layer mesh scaling and opacity falloff to simulate neon-pink atmospheric light bleed.

## Inspiration & Provenance
This repository was born from a technical exploration of the **Seeinglogic** 3D visual blog: 

*   ****Author:** Mark Griffin [@seeinglogic](https://github.com)
*   **Original Article:** [Taking the first step into 3D visuals with Python](https://seeinglogic.com)
*   **Credit:** **Seeinglogic (March 5, 2024)** — *Dev/hacker exploring software and security through visualizations.*
*   **Adaptation:** This engine extends the original icosahedron concept into an interactive, animated, and stylized "Deep Space" environment with added recursive fractal support.


## Deployment
```bash
# Initialize Environment
conda env create -f environment.yml
conda activate geometry_mesh

# Execute Supernova Engine (Auto-Orbit)
python src/supernova_render.py
