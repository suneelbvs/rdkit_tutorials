# RDKit Tutorials

This repository contains a collection of Jupyter notebooks that demonstrate common cheminformatics workflows using [RDKit](https://www.rdkit.org/). The notebooks walk through reading and writing SMILES, calculating molecular properties, generating fingerprints, and performing substructure or similarity searches.

## Prerequisites

- [Anaconda](https://www.anaconda.com/products/distribution) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
- Git (optional, but recommended if you plan to clone the repository)

## Environment Setup

1. **Clone or download the repository.**
   ```bash
   git clone https://github.com/<your-username>/rdkit_tutorials.git
   cd rdkit_tutorials
   ```

2. **Create the Conda environment.** The repository includes an environment specification at `rdkit.yml`. Create the environment with:
   ```bash
   conda env create -f rdkit.yml
   ```

3. **Verify the installation (optional).**
   ```bash
   conda env list
   ```

4. **Activate the tutorial environment.**
   ```bash
   conda activate rdkit-training
   ```

5. **Confirm the installed packages (optional).**
   ```bash
   conda list
   ```

## Running the Notebooks

With the `rdkit-training` environment active, launch Jupyter Notebook or JupyterLab:

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

Open any of the notebooks in the repository to explore the tutorials:

- `1_Reading and Writing Smiles using rdKit.ipynb`
- `2_Property calculation, Drug-like filters, and Similarity maps.ipynb`
- `3_Fingerprint Generation and Similarity Analysis.ipynb`
- `4_Substructure and Similarity Search using rdKit.ipynb`

## Data

Supporting data files referenced by the notebooks are located in the `data/` directory. Ensure you keep the directory structure intact so that relative paths in the notebooks continue to work.

## Additional Resources

- [RDKit Documentation](https://www.rdkit.org/docs/)
- [RDKit Cookbook](https://www.rdkit.org/docs/Cookbook.html)

Feel free to open issues or submit pull requests if you find problems or have suggestions for improvements.
