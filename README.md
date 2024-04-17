# Customer Purchase Analysis Project

This project aims to analyze customer purchase behavior for a small online business, with the goal of identifying patterns and insights to improve marketing strategies and increase sales. The analysis is conducted using the R programming language.

## Table of Contents

- [Introduction](#introduction)
- [Folder Structure](#folder-structure)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Understanding customer purchase behavior is crucial for businesses to tailor their marketing strategies and improve customer satisfaction. This project leverages data analysis techniques to gain insights into customer purchase patterns, segment customers based on their behavior, and make data-driven recommendations for business growth.

## Folder Structure

The project follows a structured folder organization for better organization and reproducibility:

- `data/`: Contains raw and processed data.
  - `raw_data/`: Original transactional data.
  - `processed_data/`: Cleaned and preprocessed data.
- `scripts/`: R scripts for data analysis.
  - `data_preprocessing.R`: Script for data cleaning and preprocessing.
  - `customer_segmentation.R`: Script for customer segmentation.
  - `association_analysis.R`: Script for association analysis.
  - `visualization.R`: Script for data visualization.
  - `insights_recommendations.R`: Script for generating insights and recommendations.
- `notebooks/`: R Markdown documents for analysis.
  - `exploratory_analysis.Rmd`: Exploratory data analysis.
  - `visualization_notebook.Rmd`: Data visualization.
  - `insights_report.Rmd`: Compilation of insights and recommendations.
- `reports/`: Presentation slides and project report.
  - `presentation_slides.pdf`: Presentation summarizing key findings.
  - `project_report.pdf`: Detailed project report documenting methodology, findings, and recommendations.
- `README.md`: Overview of the project.
- `requirements.txt`: List of required R packages.

## Usage

To reproduce the analysis:

1. Clone this repository to your local machine.
2. Ensure you have R installed on your system.
3. Install the required R packages listed in `requirements.txt`.
4. Run the R scripts in the `scripts/` directory in the specified order.
5. Execute the R Markdown documents in the `notebooks/` directory for exploratory analysis, visualization, and insights.
6. Review the generated reports and slides in the `reports/` directory.

## Dependencies

The project requires the following R packages:

- `tidyverse`: For data manipulation and visualization.
- `arules`: For association analysis.
- `caret`: For machine learning modeling (if applicable).
- `knitr` and `rmarkdown`: For generating reports from R Markdown documents.

Install the packages using the following command:

```R
install.packages(c("tidyverse", "arules", "caret", "knitr", "rmarkdown"))
