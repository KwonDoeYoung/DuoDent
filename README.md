# DuoDent: Tooth Generation using Dual-Stream Diffusion with Normal Consistency

![model](https://github.com/user-attachments/assets/0f03b53b-e562-4ae3-af4d-81b4d06364d3)
Welcome to the official code repository for the paper titled "DuoDent: Tooth Generation using Dual-Stream Diffusion with Normal Consistency," accepted at MICCAI 2025. In this repository, you'll find the core model classes used in the generation module.

## Abstract
Generating high-precision 3D dental data is crucial for clinical practice, virtual simulation, and education. However, it is challenging to synthesize smooth and detailed tooth models. In this work, we introduce DuoDent, a dual-stream diffusion-based framework for the synthesis of accurate 3D tooth point clouds followed by a refined mesh generation. Our framework combines Transformer-based diffusion and CNN-based diffusion to capture both global dental structures and fine local features, thereby enhancing surface detail while reducing artifacts such as staircase and rough textures. The generated point clouds are optimized using normal consistency constraints for proper alignment of surface normals, which is key to high-quality mesh reconstruction. In addition, we apply a normal estimation with orientation consistency to the generated point clouds prior to converting them to output meshes, which enables the generation of smoother and anatomically precise tooth models. Extensive experiments validate that our method not only outperforms existing approaches in quantitative metrics but also delivers superior qualitative results, demonstrating its potential to significantly improve tooth modeling in dentistry.

## Code Availability
This repository is under preparation and the code will be released **soon**.  
Stay tuned!
