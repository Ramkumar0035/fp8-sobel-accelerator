# FP8 Multiplier-Based Edge Detection Accelerator (Research Work)

## Overview
This project presents a hardware-efficient edge detection accelerator using FP8 (E4M3) floating-point arithmetic. The design integrates RGB-to-grayscale conversion and Sobel edge detection into a unified architecture optimized for FPGA-based systems.

## Research Status
This work is part of an ongoing research project submitted to IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems and is currently under review.

## Key Contributions
- Designed FP8 (E4M3) multiplier for low-power hardware acceleration
- Unified color removal and edge detection in a single architecture
- Enabled parallel convolution for real-time image processing
- Reduced hardware complexity compared to FP16/FP32 implementations

## Architecture
- FP8 multiplier with normalization and rounding
- RGB to grayscale conversion using weighted coefficients
- Sobel filtering using 3×3 convolution kernels
- Parallel processing pipeline for high throughput

## Performance
- Power reduction: up to 36%–69.6%
- Area reduction: up to 8.1%–3.3%
- Throughput: ~13 GFLOPS
- Frequency: up to ~140 MHz
- PSNR: up to 37.6 dB
- SSIM: up to 0.82

## Tools Used
- Verilog HDL
- ModelSim (Simulation)
- Quartus (FPGA Synthesis)
- Python (Image reconstruction)

## Results
The design achieves a strong balance between performance and precision, making it suitable for:
- Edge AI systems
- Embedded vision applications
- FPGA-based image processing

## Note
Some implementation details are intentionally abstracted due to ongoing research publication.
