# Time Series Forecasting in Food and Agriculture

Prerequisites:
- Login to https://gems.agroinformatics.org/webui/#
- Click `Analyze > Jupyter Notebooks`
- Open bash terminal


# Setup
1. Clone repository `git clone https://github.com/runck014/geometric-brownian-motion.git`
2. Change directory to geometric-brownian-mottion `cd geometric-brownian-motion`
3. Setup conda environment `conda env create --name timeseries-forecasting --file=environment.yml`
4. Make the environment available to Jupyter `python -m ipykernel install --user --name=timeseries-forecasting`

Test environment: 
- Click the blue plus sign to see the launcher
- You should see under "notebook", `timeseries-forecasting` as an option
- Click it to open a new notebook with that kernel
- Type and execute in the first cell `import yfinance'
- If the module loads, you've successfully completed setup

Continue to introduction-gbm.ipynb
