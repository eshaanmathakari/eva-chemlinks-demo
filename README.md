# Eva Chemlinks Dashboard

This repository contains a dashboard project developed for Eva Chemlinks. The dashboard is designed to visualize sales data and provide insightful analytics. The project is implemented using R and Python with Quarto dashboards, and it includes custom CSS for layout customization.

## Overview

The dashboard provides a streamlined workflow where new monthly data can be easily integrated. Users only need to run the preprocessing script to update the dashboard with the latest data.

## Features

- **Data Visualization**: Interactive charts and graphs to visualize sales data.
- **Custom Layout**: Aesthetic customization using CSS.
- **Streamlined Workflow**: Easy integration of new monthly data.

## Files in the Repository

- `eva-chemlinks.qmd`: The Quarto markdown file for the dashboard.
- `data-preprocess.qmd`: The Quarto markdown file for data preprocessing.
- `data/`: Directory containing the fake dataset used for the dashboard.

## Requirements

To run this project, you need the following dependencies:

- R
- Python
- Quarto
- Required R packages: `ggplot2`, `dplyr`, `shiny`
- Required Python packages: `pandas`, `matplotlib`, `seaborn`

## Setup and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/eshaanmathakari/eva-chemlinks-demo.git
cd eva-chemlinks-dashboard
```
### 2. Install Dependencies

For R-
```bash
install.packages(c("ggplot2", "dplyr", "shiny"))
```

For Python-
```bash
pip install pandas matplotlib seaborn
```
### 3. Add New Monthly Data
Place the new monthly data files in the data/ directory.

### 4. Run Data Preprocessing
Execute the data-preprocess.qmd file to preprocess the data. This will generate the necessary data files for the dashboard.

```bash
quarto render data-preprocess.qmd
```
### 5. Render the Dashboard
Execute the eva-chemlinks.qmd file to render the dashboard.

```bash
quarto render eva-chemlinks.qmd
```
Custom CSS
The layout of the dashboard is customized using a CSS file. You can modify the styles.css file to change the appearance of the dashboard.

Acknowledgments
Thanks to the Eva Chemlinks team for their support and collaboration on this project.
Special thanks to the developers of Quarto and the authors of the R and Python packages used.
