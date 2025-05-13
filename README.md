# MEP1-Quantum-Entanglement

Welcome to the MEP1-Quantum-Entanglement repository! This project implements the MEP1 (Model of Entangled Paradox Resolution 1), a 3-qubit quantum circuit designed to resolve the grandfather paradox through temporal entanglement on IBM Quantum hardware. All technical content is provided in accessible PDF format for broad usability.

## Repository Structure
```
.
MEP1-Quantum-Entanglement/
├── Calibration Report ibmq manila – Falcon r5.11H.pdf
├── LICENSE
├── MEP1-Quantum-Entanglement.pdf
└── README.md
```

- **Calibration Report ibmq manila – Falcon r5.11H.pdf**: Contains real hardware data for the `ibmq_manila` processor, including \( P(|011\rangle) = 0.318 \pm 0.02 \), \( T_1 = 75 \, \mu\text{s} \), \( T_2 = 105 \, \mu\text{s} \), and other metrics, validated as of 2022-11-13.
- **LICENSE**: Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0) governing the use of this project.
- **MEP1-Quantum-Entanglement.pdf**: Main document describing the MEP1 model, its 6-gate circuit, and results, optimized with parameters \(\theta = 2.10 \pm 0.01 \, \text{rad}\) and \(\beta = 1.20 \pm 0.01 \, \text{rad}\).
- **README.md**: This file, providing an overview and usage instructions.

## Overview

MEP1 is a computational framework that models timeline bifurcation using a 6-gate quantum circuit. It validates results against real data from the `ibmq_manila` processor, achieving a probability \( P(|011\rangle) = 0.318 \pm 0.02 \) with 92.2% fidelity, matching noise-adjusted simulations. The project has been published on Zenodo with the DOI: [10.5281/zenodo.15397516](https://doi.org/10.5281/zenodo.15397516).

## Features

- **3-Qubit Model**: Encodes timeline, grandfather state, and observer state.
- **Optimized Circuit**: 6-gate design with parameters \(\theta = 2.10 \pm 0.01 \, \text{rad}\) and \(\beta = 1.20 \pm 0.01 \, \text{rad}\).
- **Real Data Integration**: Verified with `ibmq_manila` data.
- **Accessible Format**: All content provided as PDFs for ease of use.

## Usage

- **Review**: Open `MEP1-Quantum-Entanglement.pdf` to understand the model and results.
- **Data Access**: Refer to `Calibration Report ibmq manila – Falcon r5.11H.pdf` for detailed hardware metrics.
- **Extension**: For further analysis, use the data with Qiskit or other quantum computing tools (note: source code is excluded from this repository).

## Data Notes

- **ibmq_manila**: Fully validated with real data from 2022-11-13.
- **Note**: Data for `ibmq_bogota` and `ibmq_santiago` are not included due to lack of recent real measurements. Contact the author for potential updates.

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests with additional PDFs or data. Ensure compliance with the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0), which prohibits commercial use and requires attribution to the original author.

## License

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)](LICENSE). To view a copy of this license, visit http://creativecommons.org/licenses/by-nc/4.0/ or see the `LICENSE` file for details.

## Acknowledgments

- Inspired by works from Deutsch (1991), Lloyd (2011), and the Qiskit community.
- Thanks to IBM Quantum for providing access to quantum hardware data.

## Contact

For questions or collaboration, contact Teodor Berger at bergerteodor@googlemail.com.

---
*Last updated: May 13, 2025*
