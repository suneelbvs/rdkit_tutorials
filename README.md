# RDKit Tutorials

A curated collection of Jupyter notebooks showcasing practical cheminformatics workflows with [RDKit](https://www.rdkit.org/). The tutorials start with the fundamentals of reading and writing molecules and progress to advanced topics such as reaction enumeration, conformer analysis, and building QSAR models.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Environment Setup](#environment-setup)
- [Running the Notebooks](#running-the-notebooks)
- [Tutorial Catalog](#tutorial-catalog)
- [Data](#data)
- [Additional Resources](#additional-resources)

## Prerequisites

- [Anaconda](https://www.anaconda.com/products/distribution) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
- Git (optional, but recommended if you plan to clone the repository)

## Environment Setup

1. **Clone or download the repository.**
   ```bash
   git clone https://github.com/rdkit/rdkit_tutorials.git
   cd rdkit_tutorials
   ```

2. **Create the Conda environment.** The repository includes an environment specification at `rdkit.yml`.
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

Open any of the notebooks below to explore the tutorials. Each notebook is self-contained and includes explanatory markdown cells and runnable code cells.

## Tutorial Catalog

| # | Notebook | Topic Overview |
| --- | --- | --- |
| 1 | `1_Reading and Writing Smiles using rdKit.ipynb` | Read molecules from different formats, create SMILES, and save structures. |
| 2 | `2_Property calculation, Drug-like filters, and Similarity maps.ipynb` | Calculate physicochemical properties, apply drug-likeness filters, and render similarity maps. |
| 3 | `3_Fingerprint Generation and Similarity Analysis.ipynb` | Generate fingerprints and compute similarity metrics for compound collections. |
| 4 | `4_Substructure and Similarity Search using rdKit.ipynb` | Perform substructure and similarity searches across chemical libraries. |
| 5 | `5_Conformer_Generation_and_3D_Analysis.ipynb` | Embed 3D conformers, optimize geometries, and compare conformational ensembles. |
| 6 | `6_Reaction_Enumeration_and_Scaffolds.ipynb` | Enumerate products with reaction SMARTS and analyse Bemis–Murcko scaffolds. |
| 7 | `7_Molecule_Standardization_and_Sanitization.ipynb` | Clean molecules, neutralize charges, and extract parent fragments. |
| 8 | `8_QSAR_Modeling_with_Scikit_Learn.ipynb` | Build a toy QSAR classifier from Morgan fingerprints using scikit-learn. |
| 9 | `9_Visualization_and_Drawing_Options.ipynb` | Customise 2D depictions, grid images, and similarity maps. |
| 10 | `10_Chemical_Format_Conversion_and_Metadata.ipynb` | Convert between chemical formats and preserve metadata fields. |

## Data

Supporting data files referenced by the notebooks are located in the `data/` directory. Keep the directory structure intact so that relative paths inside the notebooks continue to work.

## Additional Resources

- [RDKit Documentation](https://www.rdkit.org/docs/)
- [RDKit Cookbook](https://www.rdkit.org/docs/Cookbook.html)
- [RDKit UGM Presentations](https://www.rdkit.org/UGM/) for in-depth talks and slides.

Contributions are welcome! Open an issue or submit a pull request if you have ideas for improvements or spot any problems.
