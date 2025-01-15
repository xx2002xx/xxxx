# xxxx
## Overview

This project analyzes a dataset containing civil liberties, political rights, and regional statistics. The analysis includes descriptive statistics, correlation analysis, hypothesis testing, and eight detailed visualizations that provide insights into various aspects of the data.
###Required packages:
   `pandas`
   `matplotlib`
   `seaborn`
   `scipy`

## How to Run

1. Place the dataset file `dataset.csv` in the same directory as the script.
2. Execute the script: python data_analysis.py
3. Outputs:
   * Summary CSV files:
     * `region_summary.csv`: Regional averages of civil liberties and political rights.
     * `status_summary.csv`: Average scores by country status.
   * Analysis results:
     * `ldc_vs_non_ldc_analysis.txt`: T-test results for LDC vs Non-LDC countries.
   * Visualizations:
     * `yearly_trend_plot.png`
     * `status_distribution_plot.png`
     * `cl_vs_pr_scatter.png`
     * `cl_heatmap.png`
     * `box_plot_status.png`
## Dataset Columns

* **`country`**: Name of the country.
* **`year`**: Year of observation.
* **`CL`**: Civil Liberties score.
* **`PR`**: Political Rights score.
* **`Status`**: Country status (Free `F`, Not Free `NF`, Partially Free `PF`).
* **`Region_Code`**: UN region code.
* **`Region_Name`**: UN region name.
* **`is_ldc`**: Indicator for least developed countries (1 for LDC, 0 otherwise).
