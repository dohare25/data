# data
Processed geochemical training and test datasets for a machine-learning classifier of mantle reservoirs (DM, EM1, EM2, HIMU) using MORB and OIB trace-element data.

# Data for mantle reservoir classification (MORB and OIB)

This folder contains the processed datasets used in the study on
machine-learning classification of mantle reservoirs (DM, EM1, EM2, 
and HIMU) from trace-element data for MORB and OIB basalts.

## Contents

- `training_data.csv`  
  Processed trace-element training dataset. Each row is a sample with:
  - Sample identifier
  - Reservoir label (DM / EM1 / EM2 / HIMU)
  - Selected trace-element concentrations and ratios used as features

- `test_predictions.csv`  
  Classification results for the 15 held-out test locations using a specific AutoML framework. Columns
  include:
  - Location name (held-out test data)
  - Sample identifier
  - True reservoir label
  - Predicted reservoir label
  - Trace-element input variable data columns

- `README.md`  
  This file. Describes the structure and intended use of the datasets.

(If you include more files, list them here with a one-line explanation
each.)

## Data sources

The raw geochemical data (trace elements and isotopic
ratios) were obtained from:

- **GEOROC** – Geochemical Rock Database: https://georoc.eu  
- **PetDB / EarthChem** – https://search.earthchem.org

The query criteria, filtering steps, and reservoir assignments are
described in detail in the associated manuscript.

## Usage

These datasets are provided to allow users to:

- Reproduce the training and evaluation of the AutoML classification framework
- Explore alternative classification methods
- Perform additional sensitivity tests on feature sets or reservoir
  definitions

Please cite the associated journal article and this repository (or its
Zenodo DOI) if you use these data in your own work.

## Contact

For questions about these data or their use, please contact:

Daniel O'Hare, Loma Linda University, dohare@students.llu.edu 
