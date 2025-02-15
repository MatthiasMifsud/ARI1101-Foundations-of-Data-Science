# ARI1101 - Foundations of Data Science

## Beijing Air Quality Analysis

This repository contains an analysis of Beijing's air quality data using R Markdown, Flexdashboard, and Shiny. The project includes interactive visualizations and statistical insights based on the chosen dataset.

## Repository Contents

- **`flexdashboard.rmd`**  
  This file contains the R Markdown code to generate an interactive web-like representation of the air quality data. The implementation uses **Flexdashboard** and **Shiny servers** to enhance interactivity.

- **`flexdashboard.html`**  
  The knitted HTML output from `flexdashboard.rmd`. Graphs and interactive elements may not be visible when opened locally, as they require a running Shiny server.

- **`documentation.rmd`**  
  This R Markdown file generates `documentation.pdf`, which provides detailed information and visualizations regarding Beijing's air quality, derived from the selected dataset.

- **`documentation.pdf`**  
  A PDF report containing statistical insights and visualizations on Beijing's air quality.

- **CSV Datasets**  
  The raw and cleaned datasets used for analysis.

## Installation & Usage

To run the interactive dashboard locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ARI1101-Data-Science.git
   cd ARI1101-Data-Science
   ```
2. Open `flexdashboard.rmd` in RStudio.
3. Install necessary R packages (if not already installed)
4. Click **Run Document** in RStudio to launch the dashboard.

## Notes
- Ensure that **Shiny** is running for the interactive elements to work.
