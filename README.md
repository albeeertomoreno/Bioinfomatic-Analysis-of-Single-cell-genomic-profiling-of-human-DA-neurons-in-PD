# Proposal for an Improved Bioinformatic Analysis based on data from "Single-cell genomic profiling of human dopamine neurons identifies a population that selectively degenerates in Parkinson’s disease"

## Project Description

## Key Components

- **Exploratory Data Analysis**:
- **Model Training**:
- **Model performance evaluation**:
- **Overfitting Analysis**:

## Project structure

    .
    ├── code/
    │   └──
    ├── Date/
    │   ├──
    ├── notebooks/
    ├── src/                                #
    |   ├── _init_.py                       # 
    │   ├── .py                          # 
    │   ├── .py                       # 
    │   ├── .py                    #
    ├── .gitignore
    ├── single_cell_PD.yml            # Micromamba environment dependences to ensure reproducibility
    ├── README.md
    └── setup.py            # Package setup python script used for editable pip installation

## Installation

### 1. Prerequisites

**Micromamba:** Used for setting a reproducible python virtual environment

**Jupyter Lab or Jupyter Notebook:** Used to run all the notebooks containing the analyses

### 2. Clone the Repository

Clone the assignment repository to your local machine and cd into it.

git clone [[single_cell_PD](https://github.com/NeoCorteX33/Bioinfomatic-Analysis-of-Single-cell-genomic-profiling-of-human-DA-neurons-in-PD.git)]

cd single_cell_PD

### 3. Setup micromamba environment

Create environment and activate the micromamba environment by:

micromamba env create -f single_cell_PD.yml

micromamba activate single_cell_PD

### 4. Install the project as an editable package using pip

pip install -e .

## Usage guidlines

1. Launch Jupyter Lab or Jupyter Notebook from the project's root directory while your micromamba environment is activated.

2. Navigate to the notebooks/ directory.

3. Open the notebooks sequentially first EDA.ipynb and then ML_analysis.ipynb .

4. **Important:** Ensure that the notebooks you opened are using the ex_2 as the python kernel.
