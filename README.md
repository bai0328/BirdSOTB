# BirdSOTB: A Benchmark for Bird Single Object Tracking to Support Navigation Services

BirdSOTB is a specialized benchmark dataset designed for **Single Bird Object Tracking**, aimed at supporting aviation safety, ecological monitoring, and autonomous navigation services.


## Project Overview

Visual object tracking of birds faces unique challenges such as high-speed maneuvers, extremely small target sizes, frequent occlusions, and motion blur. BirdSOTB provides a high-quality, manually annotated dataset to support specialized bird tracking research.

### Key Features

- **Specialized Dataset**: 14 video sequences with 5,489 frames, specifically focusing on bird targets.
- **Diverse Challenges**: Covers Fast Movement (FM), Small Target (ST), Occlusion (POC/FOC), Out-of-View (OV), and Motion Blur (MB).
- **Quantitative Evaluation**: A rigorous quantitative attribute evaluation system based on multiple metrics (Scale Ratio, Area Ratio, Normalized Speed, etc.).
- **High-Precision Annotation**: All sequences are manually annotated with high precision to ensure geometric consistency.

## Data Examples

![Example Data](./figures/fig1.png)
*Fig 1. Example data from BirdSOTB showing target pixel-level dimensions and motion/size changes.*

![Distribution Analysis](./figures/fig2.png)
*Fig 2. Distribution analysis of bounding box area (Percentage and Pixel) via KDE.*

## Qualitative Evaluation

![Qualitative Evaluation](./figures/fig3.png)
*Fig 3. Qualitative evaluation of challenging sequences in the BirdSOTB dataset.*

## Availability

- **Dataset & Code**: Coming soon.

---
© 2026 BirdSOTB Team. All rights reserved.
