# Atlanta Home Rental Analysis

This project is aimed at predicting the prices of home rentals in the Atlanta area using data scraped from GAMLS.

## Usage

To predict the price of a home rental, simply run the ``predict_price.py`` script with ``python3 predict_price.py`` and enter in the details about the home rental. If some attributes are unknown, just enter "na" for them, and the model will impute their values.

The datasets used are located in [data](/data/). The Jupyter notebooks for data analysis are located in [analysis](/analysis/). ``exploration.ipynb`` deals with the cleaning, preprocessing, and preliminary analysis of the data, while the machine learning models are created and evaluated in ``models.ipynb``.