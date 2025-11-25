# IBM Coursera — Deep Learning with PyTorch, Keras and TensorFlow

Brief collection of personal notes, example notebooks and exercises for the "Deep Learning with PyTorch, Keras and TensorFlow" Coursera course. This repo holds code, experiments and small datasets used while following the course.

## Repo layout
- `notebooks/` — Jupyter notebooks for each module (PyTorch, Keras, TensorFlow)
- `README.md` — this file

## Requirements
- Python 3.8+ (3.9/3.10 recommended)
- Git, JupyterLab / Jupyter Notebook
- CUDA toolkit (optional, for GPU). Use CPU if not available.

## Quick start (venv)
1. Clone the folder to your machine.
2. Create and activate a virtual environment:
    - Windows:
      - python -m venv .venv
      - .venv\Scripts\activate
    - macOS/Linux:
      - python3 -m venv .venv
      - source .venv/bin/activate
3. Install dependencies:
    - pip install -r env/requirements.txt
4. Launch notebooks:
    - jupyter lab
    - Open notebooks from `notebooks/`

Or using conda:
- conda env create -f env/environment.yml
- conda activate dl-course

## Usage
- Run notebooks in order to reproduce learning examples.
- Use `scripts/train_*.py` for CLI-based experiments.
- Replace/sample datasets in `data/` with your own when needed.

## Notes and best practices
- Keep GPU drivers and CUDA matched to your chosen PyTorch/TensorFlow builds.
- Use small subsets of data while iterating to speed up development.
- Commit your notebooks selectively; consider using tools like nbstripout to remove outputs.

## Contributing
- Add notes, improved examples or reproducible scripts for exercises.
- Use clear commit messages and include tests/demo notebooks when possible.

## License
- This repository contains personal study material and examples. Add an appropriate license file (e.g., MIT) if you intend to share publicly.

## Acknowledgements
- This folder is organized while following the Coursera course. For the official course content and syllabus refer to the course provider (Coursera / IBM) directly.

If you want, I can create a starter `requirements.txt`, a sample notebook template, or an `environment.yml` now.