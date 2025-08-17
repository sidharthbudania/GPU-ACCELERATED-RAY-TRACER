# GPU-Accelerated Ray Tracer

This project is a CUDA-based ray tracer implemented in C++ that renders photorealistic images using path tracing techniques.  
It demonstrates the use of GPU acceleration to achieve significant performance improvements over traditional CPU-based rendering.

## Features
- **Physically-Based Rendering**: Implements Lambertian (diffuse), metallic (reflective), and dielectric (glass-like) materials with Fresnel effects.
- **Monte Carlo Path Tracing**: Uses random sampling and multi-sample averaging to simulate global illumination and soft shadows.
- **GPU Acceleration with CUDA**: Parallelized pixel rendering with CUDA kernels for faster computation.
- **Configurable Camera System**: Supports depth of field, aperture, and adjustable focus distance.
- **Image Export**: Outputs rendered images in PPM format at configurable resolutions.
