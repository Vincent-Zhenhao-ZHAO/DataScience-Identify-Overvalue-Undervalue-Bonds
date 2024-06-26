# Identifying Overvalued and Undervalued Bonds for Daily Capture through Data-Driven Analysis.

## Project Description
This project involves in-depth analysis and visualization of bond market data, focusing on attributes such as coupon rates, bid-ask spreads, index prices, and more. The analysis aims to reveal key insights into the distribution and interrelationships of bond market characteristics.

## Project Overview
Mispricing of fixed-income assets, particularly bonds, can challenge investors seeking to determine accurate valuations. This study proposed two models for identifying potentially overvalued and undervalued bonds by employing the metrics of yield to maturity (YTM) and option-adjusted spread (OAS). The study used duration and DV01 (dollar value of an 01) to corroborate these findings. The research also explored how non-financial institutions can influence bond mispricing, especially in the oil and gas sector. While limited historical data prevented in-depth precision evaluation of the result, this study still provided a valuable framework for further exploration.

## Project Background
The project was based on the Data Solving Challenge, organised by pre-S&P CTO Yaacov Mutnikas. The dataset is about the iBoxx USD liquid investment with an investment-grade dataset, which offers an end-of-trading day (January 25, 2016) capture of investment-grade bonds in US dollars, with ratings assigned by S&P. This is an open project, and we need to do a huge EDA process to find the valuable points to work on. Thanks to the guidance of Yaacov Mutnikas, I can propose a novel way to identify the overvalued and undervalued bonds. This project took me about 2 weeks to finish. 

## Limitation
### Research Limitation
- The analysis lacks a strict precision test to verify the overvaluation or undervaluation of bonds, primarily due to a limited historical dataset.
- The evaluation rests upon assumptions regarding overvalued and undervalued bonds, which may not fully describe the bonds' characteristics.
- The dataset is derived from a single-day snapshot, which prevents an in-depth exploration of variables such as spot price growth or YTM fluctuations.
### Code Limitation
Due to the time constraint, I didn't have time to explain the code nicely in Markdown, and it would have looked very confusing to you. You may need to follow the structure of the code that loads the data, clean the data, EDA process, network process, and undervalue & overvalue identification. In the next step, I will clean up the code and make it accessible and readable.

## Features

### Data Loading and Preprocessing
- **Tools Used**: Pandas
- **Purpose**: Efficient data loading from Excel spreadsheets and initial data preprocessing.

### Data Analysis
- **Focus**: Detailed examination of various bond attributes to understand market dynamics.
- **Techniques Used**: Statistical summaries, frequency distributions, and correlation analyses.

### Visualization
- **Libraries Used**: Plotly, Matplotlib, Seaborn, NetworkX
- **Features**: Creation of interactive plots and network graphs to visualize complex relationships and trends within the bond market.

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

- Python 3.x
- Jupyter Notebook

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Vincent-Zhenhao-ZHAO/DataScience-Identify-Overvalue-Undervalue-Bonds.git
   ```
2. Install the required Python packages:
   ```sh
   pip install numpy pandas matplotlib seaborn plotly networkx holoviews pyvis
   ```
3. Launch the Jupyter Notebook to explore the analyses:
   ```sh
   jupyter notebook Code.ipynb
   ```
## Getting Started
Contributions to extend or enhance the project are welcome. Follow the typical fork-branch-PR workflow.

## License
Distributed under the MIT License. See LICENSE for more information.
   
