# Gaia Variable Star Explorer

This repository contains the Jupyter Notebook `GaiaVariableStarExplorerNotebook.ipynb`, which provides tools for exploring and analyzing variable stars using data from the Gaia satellite. It includes code and explanations for processing and interpreting astronomical data.

## Research Context
This project emerged from personal research on stellar astronomy conducted between June 2023 and December 2024. The work was:

- Published in the Journal of Emerging Investigators (JEI) following three revision cycles
- Awarded Third Prize in Physics and Astronomy at the Taiwan International Science Fair (January 2024)
- Won Second Prize in Physical Sciences at MOSTRATEC International Science Fair in Brazil (October 2024)

## Features

* **Data Import and Processing**: Load star cluster data from Excel files.
* **Statistical Analysis**: Compute correlations and regression models to identify relationships in the data.
* **Parameter Optimization**: Use algorithms to find optimal parameters for the best fit.
* **Visualization**: Generate scatter plots, regression lines, and confidence intervals to visualize data relationships.

## Prerequisites

* Python 3.x
* Libraries: `numpy`, `matplotlib`, `scipy`, `openpyxl`

Install the required libraries using:

```bash
pip install numpy matplotlib scipy openpyxl
```

## Data Files

* `GCdata.xlsx`: Raw observational data from research on globular clusters, including measurements and parameters collected during the study. This file contains the unprocessed data that will be analyzed.

Ensure your data files match the format specified in the notebook. Data in the provided Excel file may not be up to date with the newest observations.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/GaiaVariableStarExplorer.git
```

2. Navigate to the repository directory:

```bash
cd GaiaVariableStarExplorer
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook GaiaVariableStarExplorerNotebook.ipynb
```

4. Run the cells sequentially to load data, process it, and visualize the results.

## Key Outputs

* **Optimized Parameters**: Displays the best-fit parameters for regression models.
* **Correlation Coefficients**: Evaluates relationships between star properties.
* **Visualization**: Graphical representation of regression fits and data trends.

## Example Plots

* Scatter plots of `log(RRppm)` vs. `Optimized_X`.
* Linear regression line with a 95% confidence interval overlay.

## Contributing

Contributions are welcome! If you find a bug or have suggestions for improvement:

1. Fork the repository.
2. Create a new branch for your feature.

```bash
git checkout -b feature-name
```

3. Commit your changes:

```bash
git commit -m "Description of changes"
```

4. Push the branch and create a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.