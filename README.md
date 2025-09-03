# Quantum Principal Component Analysis (QPCA) Research

A comprehensive implementation and benchmarking study comparing quantum and classical approaches to Principal Component Analysis.

## Overview

This repository contains experimental implementations of quantum PCA algorithms alongside classical baselines to systematically evaluate when quantum approaches might offer practical advantages. The focus is on rigorous performance analysis rather than theoretical claims.

## Algorithms Implemented

### Classical Methods
- Standard PCA (SVD-based)
- Randomized PCA
- Incremental PCA
- Kernel PCA

### Quantum Methods  
- VQE-based QPCA
- QAOA-based QPCA
- Hybrid classical-quantum approaches
- Quantum-inspired classical variants

## Key Features

- **Systematic Benchmarking**: Fair comparison framework for quantum vs classical methods
- **Real Hardware Integration**: Support for IBM Quantum devices with noise characterization
- **Reproducible Experiments**: All results include statistical analysis and error bars
- **Scalability Analysis**: Performance tracking across different problem sizes
- **Noise Simulation**: Realistic noise models for quantum algorithm evaluation

### Requirements
- Python 3.8+
- Qiskit 0.45+
- scikit-learn
- numpy, scipy, matplotlib
- jupyter (for notebooks)

## Contributing

This research is focused on rigorous experimental validation. Contributions should include:
- Proper statistical analysis and error reporting
- Reproducible experimental setups
- Clear documentation of assumptions and limitations

## Citation

```bibtex
@misc{qpca_research_2024,
  title={Quantum Principal Component Analysis: A Systematic Implementation Study},
  author={Pablo Herrera},
  year={2025},
  url={https://github.com/D4rk-h/Quantum-PCA}
}
```

## License

Apache 2.0 - <a href='LICENSE'>See LICENSE file for details</a>