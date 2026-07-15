# Quantum Computing-Inspired SAW Enumeration (2D & 3D Lattices)

This repository contains the complete implementation of a **quantum-inspired classical algorithm** for the exact enumeration of self-avoiding walks (SAWs) on 2D square and 3D cubic lattices.

The algorithm is based on **Quantum Amplitude Estimation (QAE)** combined with Grover’s search and Inverse Quantum Fourier Transform, but it is **optimized to run on classical hardware** using the Qiskit Aer simulator. It employs hybrid simulation techniques (qubit reinitialization, tensor-network-style compression, and Zero-Noise Extrapolation) to make large-scale exact enumeration feasible.

## Key Features
- Exact enumeration of SAWs (not statistical sampling)
- Supports 2D square lattice up to **N = 71 steps**
- Supports 3D cubic lattice up to **N = 40 steps**
- Significant reduction in computation time compared to classical methods
- Hybrid quantum-classical simulation strategy for scalability
- Fully reproducible with provided scripts

## Citation
If you use this code in your research, please cite our paper:

> H. Mishra *et al.*, "Quantum Computing Inspired Approach for Self-Avoiding Walk (SAWs): 2D lattice and 3D lattice SAWs for single chain enumeration" (2026).

## Requirements
- Python 3.10+
- Qiskit 2.0+
- Qiskit Aer 0.16+
- NumPy, Matplotlib (for visualization)

## Installation
```bash
git clone https://github.com/with-hemant/Quantum-amplitude-estimation.git
cd Quantum-amplitude-estimation
pip install -r requirements.txt
