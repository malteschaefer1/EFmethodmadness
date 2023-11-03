# Emission Factor Method Madness (working title)

An in-depth study into the methodological aspects of grid emission factor calculations. This code is the computational engine under the hood of the study "Towards Standardized Grid Emission Factors: Methodological Insights and Best Practices" to be submitted soon. The preprint can be found at [arXiv](https://arxiv.org/abs/2311.01103). Find a release version of the code [here](https://doi.org/10.24355/dbbs.084-202309131139-0) and of the data [here](https://doi.org/10.24355/dbbs.084-202309111514-0).

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Contribution](#contribution)
- [Versioning](#versioning)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

## Installation
If you want to run the notebook without installation, check out [Jupyter](https://jupyter.org/try). Otherwise, you will need to install Python 3.

### Dependencies
All the required packages are listed in 4_env/environment.yml.

### Steps
If you want to reproduce the results, just execute the cells in the notebook one after the other. I did not upload any intermediate results, as the files are too large. Also, I could not upload ENTSO-E data, as the data is not licensed in a way that allows sharing via Github. You can get ENTSO-E data from the [ENTSO-E Transparency Portal](https://transparency.entsoe.eu/).

## Usage

### Basic Usage
1. Download missing ENTSO-E data (AGPT and PF) into 1_data/1_raw/ENTSOE (see ###Steps).
2. Run the notebook in 3_notebooks.
3. Play around with it, change, add, have fun.

### Advanced Usage
As time advances, advanced usage will be documented here.

## Code Structure
The following refers to the file main.ipynb:
1. The first part is mostly about wrangling with the input data, including mapping categories onto one another.
2. The second part is mostly about calculating the various configurations of grid emission factors.
3. The third part is mostly about creating plots from the data.

## Contribution
All the code you see here was written by me, Malte Schäfer. Generative AI has contributed in the code generation, including debugging.

## Versioning
So far, this is the first version. I will update this section as the respository evolves.

## License
This project is licensed under the MIT License - see LICENSE.md file for details.

## Contact
You can contact me here via Github.

## Acknowledgments
The research and code writing was funded by the Federal Ministry for Economic Affairs and Climate Action (BMWK) as part of the research project ’flexess’ under Grant No. 03EI4005A.
