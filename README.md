# Weather Predictions with Machine Learning


## About
I am looking at various ways to use ML with weather patterns. This repo was created by following a tutorial: [Predict the Weather with Machine Learning](https://www.youtube.com/watch?v=km95-NMT6lU) by Vik Paruchri with Dataquest.

## Model

$$\sum_{i=1}^n (y_i - \sum_{j=1}^p x_{ij}\beta_j)^2 + \lambda \sum_{j=1}^p \beta_j^2$$


## Data

Data was requested through the National Oceanic and Atmospheric Administration and National Centers for Environmental Information's [Climate Search request pages](https://www.ncdc.noaa.gov/cdo-web/search). Parameters of search requested were "Daily Summaries" taken from the Louisville Muhammad Ali Airport (SDF) from January 1, 1960 to June 28, 2022.

The five core weather patterns are established from the documentation[^1] and include the following values per day:

1. Precipitation in inches
2. Snowfall total in inches
3. Snow depth (ground accumulation) in inches
4. High temperature in Fahrenheit
5. Low temperature in Fahrenheit

## Running the Program

### Requirements

Anaconda is the preferred distribution and contains all the required packages needed to run this program.

If you would rather install individually:

    pip install jupyter
    pip install pandas
    pip install -U scikit-learn
    pip install matplotplib
    pip install numpy

### Steps

1. Clone or download the repo
2. In the root folder of the repo, install requirements (if not using Anaconda).
3. Open the `weather.ipynb` notebook with `jupyter notebook` in the terminal, or open with editor.
4. Click "Run All"

Clear the kernel and restart the notebook as needed.

## Footnotes
[^1]: See GHCND_documentation.pdf for the Global Historical Climatology Network.