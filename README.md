# MTF & DQE in Electron Microscopy

A step-by-step tutorial for understanding and analyzing the Modulation Transfer Function (MTF) and Detective Quantum Efficiency (DQE) in imaging, with a focus on Transmission Electron Microscopy (TEM).

## Overview
This repository provides a practical, beginner-friendly introduction to MTF and DQE concepts as they apply to imaging systems, especially in electron microscopy. You will learn how to compute, visualize, and interpret these metrics using Python. The tutorial is suitable for students, researchers, and practitioners in physics, materials science, and related fields who are interested in quantitative image analysis and instrument performance assessment.

## Getting Started

### Prerequisites
- Python 3.8+
- [uv](https://github.com/astral-sh/uv) (for dependency management)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mtf_dqe.git
   cd mtf_dqe
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   uv pip install -r requirements.txt
   # or use pyproject.toml with uv
   uv pip install
   ```

## Usage
The main tutorial is provided in the `MTF_DQE.ipynb` Jupyter notebook. Open it with:
```bash
jupyter notebook MTF_DQE.ipynb
```
The notebook walks you through the theoretical background and practical computation of MTF and DQE, including:
- Introduction to MTF and DQE in the context of imaging and TEM
- Frequency domain analysis and visualization
- Step-by-step code examples with explanations
- Interpretation of results and practical tips

Follow the instructions and code cells in the notebook.

## Project Structure
- `MTF_DQE.ipynb` — Main tutorial notebook (MTF & DQE for TEM imaging)
- `pyproject.toml`, `uv.lock` — Dependency management
- `.venv/` — Virtual environment (not tracked by git)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing
Pull requests and issues are welcome! Please open an issue to discuss your ideas or report bugs.

## Author
lpetrov

## Further Reading
- [Introduction to the Modulation Transfer Function (MTF)](https://www.sciencedirect.com/topics/engineering/modulation-transfer-function)
- [Detective Quantum Efficiency (DQE) in Electron Microscopy](https://www.nature.com/articles/s41598-020-70855-6)
- [Transmission Electron Microscopy: Physics of Image Formation](https://www.springer.com/gp/book/9783662564941)

---
Happy learning!