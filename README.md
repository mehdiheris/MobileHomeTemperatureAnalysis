# Mobile Home Data Analysis

## Overview

This repository contains the data and code accompanying a research publication on indoor heat vulnerability and cooling strategies in mobile home communities. The project uses Python-based data analysis and visualization techniques to explore housing conditions and thermal exposure.

The analysis is documented in:

* `MobileHomeDataAnalysisNotebook.ipynb`

## Associated Publication

**Title:**
*Assessing Indoor Heat Vulnerability and Cooling Strategies in Three Mobile Home Communities in Boulder, Colorado, USA*

**Authors:**
Mehdi P. Heris
Skye Niles
Alana Wilson
Megan McCurdy
Amy Lacourse
Nick Lankau

**Link:**
[Insert URL Here]

If you use this repository, please cite the publication above.

## Data

* `data.csv` — Dataset used for analysis in the study.

### Data Disclaimer

To ensure anonymity and protect privacy, several mobile home entries were excluded from the dataset due to their potential identifiability.

As a result:

* The dataset included here is a modified version of the original dataset used in the publication.
* Summary statistics (e.g., averages) may differ slightly from those reported in the published paper.
* This repository is intended to support transparency and reproducibility of methods rather than exact numerical replication.

## Repository Structure

* `MobileHomeDataAnalysisNotebook.ipynb` — Main notebook with data processing, analysis, and visualizations.
* `data.csv` — Processed dataset used in the analysis.

## Requirements

Install the required Python packages:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. Open and run:

```
MobileHomeDataAnalysisNotebook.ipynb
```

## Reproducibility Notes

* Ensure all dependencies are installed.
* Confirm file paths to `data.csv` are correct.
* Minor differences in results may occur due to anonymization-related data exclusions.

## Acknowledgements

This work is partially funded by the Outreach Grant Program of the University of Colorado Boulder (2018).

We extend our deepest gratitude to the residents of the mobile home parks who participated in this study. Their willingness to engage with our research team and share their personal experiences and living conditions was invaluable to this research. Their contributions went beyond merely participating in surveys and allowing us to monitor temperatures within their homes; they provided critical insights that shaped the findings and conclusions of this study.

We are especially thankful for their openness and hospitality during our visits and their continued engagement throughout the study period. This research would not have been possible without their generous participation and support.

We conducted this research in line with the University of Colorado Boulder IRB protocol 17-0412. All research participants gave informed consent to be included in the study.

## License

Specify your license here (e.g., MIT License).

## Contact

For questions, feedback, or collaboration inquiries, please open an issue or contact the repository owner.
