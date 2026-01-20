# Gold Price Forecasting (ARIMA & RNN Family)

Forecasting gold futures prices using classical time-series models (ARIMA) and deep recurrent networks (RNN, LSTM, GRU, BiLSTM). The project explores multiple notebook experiments on cleaned gold price datasets.

## Repository Layout
- Data/: Raw and cleaned gold price CSV files.
- Code (fixed)/: Utility code used by the notebooks.
- Output (HTML)/: Saved notebook outputs/visualizations in HTML.
- *.ipynb: Experiment notebooks (ARIMA, RNN, LSTM variants, GRU, BiLSTM, preprocessing, and exploratory stats).

## Getting Started
1. Clone the repo: `git clone https://github.com/VyMinh/DAB_Project.git`
2. (Optional) Create and activate a virtual environment.
3. Install dependencies (adjust versions as needed):
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn statsmodels tensorflow notebook
   ```
4. Launch Jupyter and open the notebooks:
   ```bash
   jupyter notebook
   ```

## Notebooks Guide
- Data_Preprocessing.ipynb: Cleans and prepares gold price data.
- Data-Stats.ipynb: Exploratory statistics and visualizations.
- ARIMA.ipynb: Baseline classical forecasting.
- RNN.ipynb / LSTM.ipynb / LSTM-before.ipynb / GRU.ipynb / GRU_fixed.ipynb / BiLSTM.ipynb: Neural forecasting experiments and comparisons.

## Data
Gold price CSVs live in Data/. Ensure the working directory is the repo root when running notebooks so relative paths resolve correctly.

## Tips
- If you add new libraries, capture them in a requirements file for reproducibility.
- Export results to Output (HTML)/ to keep rendered notebooks versioned.
