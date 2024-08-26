# Economic Indicators and Housing Affordability Analysis

## Project Overview
This project aims to analyze the relationship between various economic indicators, such as mortgage rates, income levels, and housing affordability, over time. By exploring these factors, the project seeks to answer key questions such as whether life has become more expensive.

## Contributors
- [Mason Galusha](https://github.com/MLGalusha)
- [Marquez Ward](https://github.com/mdward911)
- [John Wolfe](https://github.com/j-wolfe5)
- [Stacy Magwano](https://github.com/stacjstaton)

## Data
We primarly used Federal Reserve Econmic Data(FRED) api to gather most of the datasets. For the most part the data was relativly clean which was expected since it was federal data. The main issue was FRED's datasets were very small portions of data, so we had to collect a lot of different data sets as well as use statistics to understand the data better.

- [Proposal](https://docs.google.com/document/d/1A5-LTtKCHrmuNyJga9NzKMxSI5OlEouVu_Cpf4sOPb4/edit)
- [Presentation](https://docs.google.com/presentation/d/1Hqvb2rRlxx34wJOdOkd6x-wsCru26VunCuMzxu0agRI/edit#slide=id.p)

## Key Findings

### 1. Income & Housing
**Income vs. Housing**

- Housing and Income rise at an realatively equal rate showing that they are correlated
- Even though housing and income rise at a similar rate housing prices have gone up signifigantly more(17x more to be exact)!

![Income vs. Housing](graphs/income_vs_housing.png)

### 2. Mortgage Rate & Affordability
**Mortgage Rate vs. Housing Affordability**

- There is a positive correlation between Mortgage Rate and Housing Affordabiliy.
- The correlation shows that the lower the mortgage rate the more affordable the housing was.
- It makes sense now but at first that came as a surprise to use just because we thought of affordability correlation more with house price itself than mortgage rate(as mortgage rate dropped house prices went up making us think that affordability has more to do with mortgage rate)

![Mortgage Rate vs. Housing Affordability](graphs/mortgage_rate_scatt.png)

### 3. Trends Found
**Pandemic vs. Economy**

- As we expected before starting this project we noticed spikes during the pandemic.
- This gave us some very interesting insight to what covid was affecting and what it was not affecting(not affecting as much).
- Out of all of our data Mortgage Rates, Gas prices, and housing spiked the most and for the most part up until end of 2023 haven't recovered.

![Economic Change](graphs/change_over_time.png)


## Conclusions

- Higher mortgage rates lead to lower housing affordability, making homes harder to purchase during periods of high rates.
- Housing prices have risen faster than incomes, making homeownership increasingly difficult for the average person.
- Adjusted for inflation, income growth has been modest, reducing purchasing power and affecting affordability.
- Economic downturns, like the 2008 crisis, and 2020 pandemic impacted housing prices and rates but didn’t improve affordability arguably made it worse.
- The cost of living has outpaced income growth, particularly in urban areas, increasing financial strain on households.
- Housing affordability is influenced by more than just income and mortgage rates, with broader economic conditions playing a significant role.
- Long-term housing affordability has declined, indicating a need for policies that make housing more accessible.

## Future Work

- Investigate much deeper into every aspect of the economy and of the overall United States
- Compare different areas around the United States and find correlations and trends between the economies.
- Explore different datasets like demographics to figure out if any of it affects the economy
- Add time series forecasting to predict whats going to happen in the next couple years(probally need A LOT of data to accuratly predict the economy)
- Explore policies and how much certain policies affect the econonmy.
- How the other countries affect the American Economy

## How to Run this Project

### Prerequisites

1. **API Key from the Federal Reserve Bank of St. Louis**:
   - Obtain an API key by following this [link](https://fredaccount.stlouisfed.org/apikeys).
   - Store the API key in a file named `keys.env` in the project directory.

2. **Python**:
   - Ensure Python is installed (version 3.6 or higher recommended).
   - If Python is not installed, download and install it from the [official website](https://www.python.org/downloads/).

3. **Required Python Packages**:
   - Install the necessary packages using the following command:
     ```bash
     pip install pandas python-dotenv requests matplotlib
     ```
   - These packages include `pandas` for data manipulation, `python-dotenv` for environment variable management, `requests` for handling HTTP requests, and `matplotlib` for data visualization.

### Running the Jupyter Notebooks

To explore the analysis provided in this project, follow the steps below to run the Jupyter notebooks.

#### Option 1: Using Visual Studio Code (VSCode)

1. Clone this repository to your local machine.
2. Open the desired notebook in VSCode.
3. Use the "Run All" button to execute all cells and generate the analysis and visualizations.

#### Option 2: Using Jupyter Notebook

1. Open a terminal and navigate to the directory containing the notebook files.
2. Start the Jupyter Notebook server by running:
   ```bash
   jupyter notebook

## Thoughts
   Working on this project was both a fun and insightful experience. We dug into economic data and learned a lot about how factors like mortgage rates, income, and inflation influence housing affordability. It was fascinating to see how these elements interact and shape the broader economy.

   Beyond just crunching numbers, we really sharpened our skills in data analysis and statistics. This project pushed us to think critically, interpret data carefully, and present our findings in a way that makes sense to others.

   In the end, we didn’t just answer our initial questions—we also uncovered insights that could guide future research. This project was a great blend of challenge and learning, leaving us with a deeper understanding of both the economy and the power of data.

## Contributors
<a href="https://github.com/MLGalusha/data-analysis-project1/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=MLGalusha/data-analysis-project1" />
</a>