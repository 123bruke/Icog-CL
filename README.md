# Icog-CL

A Jupyter Notebook project exploring **continual learning**—the ability of a machine-learning model to learn from a sequence of tasks or data while retaining knowledge acquired previously.

## Project contents

- [`continual-learning-project.ipynb`](continual-learning-project.ipynb) — the main notebook containing the project workflow, experiments, visualizations, and results.

## Getting started

### Requirements

- Python 3.9 or later
- Jupyter Notebook or JupyterLab
- The Python packages imported in `continual-learning-project.ipynb`

### Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/123bruke/Icog-CL.git
   cd Icog-CL
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```

   On Windows PowerShell, use:

   ```powershell
   .venv\Scripts\Activate.ps1
   ```

3. Install Jupyter:

   ```bash
   python -m pip install --upgrade pip jupyterlab
   ```

4. Install the additional dependencies used by the notebook. Review the import cells in `continual-learning-project.ipynb` and install any missing packages, for example:

   ```bash
   pip install <package-name>
   ```

5. Start JupyterLab:

   ```bash
   jupyter lab
   ```

6. Open `continual-learning-project.ipynb` and run the cells from top to bottom.

## Recommended workflow

For reproducible results:

- Run the notebook in a clean virtual environment.
- Execute cells in order rather than relying on an existing kernel state.
- Record the Python version, package versions, and any dataset or model configuration used for an experiment.
- Restart the kernel and rerun all cells when comparing experiments.

## Results

The notebook is the source of truth for the project's experiment outputs, charts, and observations. After running it, review the generated visualizations and evaluation metrics to assess learning performance and retention across tasks.

## Contributing

Contributions are welcome. To propose an improvement:

1. Fork the repository.
2. Create a feature branch.
3. Make and test your changes.
4. Open a pull request with a clear explanation of the change.

When updating the notebook, keep explanatory markdown, code, and outputs organized so that the complete workflow can be reproduced by another contributor.

## License

No license has been specified for this repository yet. Until a license is added, all rights are reserved by the copyright holder.
