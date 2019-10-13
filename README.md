# Project Title

For my MBA at the OneMBA at the RSM I investigated Burger King as part of the Marketing curriculum.
The 4Ps (Product, Place, Price, Promotion) make up a typical marketing mix. For the Place attribute I looked at Burger King location in The Netherlands:
- What is the point of sale for Burger King?
- What are the decision criteria for Burger King to decide in a specific location?
See also the WIKI page https://github.com/leonsmiers/burgerking-Google-datascience/wiki

## Getting Started
Two Jupyter notebooks are used:
1.Burger King locations.ipynb
  Make callouts to Google APIs and combine the result into a set of DataFrames
  The result is written into a csv file for hand-over to the next Jupyter notebook
2.Investigate BK Data.ipynb
  The resulting cvs file from the first step is investigated and results into a graph

(1) Jupiter notebooks
  All Python based
  Burger King locations.ipynb Uses Google Place APIs googlemaps library Output: set of CSV files containing location detail information for every company investigated
  Investigate BK Data.ipynb Data Science classification code sklearn RandomForest
(2) Output results (Excel and CSV)
  Burger King NL places.xlsx
  Output from "Burger King locations.ipynb" Y-score-McD.xlsx Y-score-BK.xlsx X-scores-McD.xlsx X-scores-BK.xlsx

### Prerequisites
1. Google MAP APIs, Python, Data Science with the sklearn library and (of course) Jupyter are the basis for this project.
2. Access to Google APIs (credit card required)
3. Required tooling
- Anaconda Jupyter
- Python libraries
  - sklearn
  - matplotlib
  - googlemaps
  - csv

### Installing
pip install googlemaps
pip install -U google-api-python-client

## Running the tests


### Break down into end to end tests


### And coding style tests


## Deployment

Load the notebooks into Jupyter

## Built With

## Contributing


## Versioning


## Authors

* **Léon Smiers** - *Initial work* - [Léon Smiers](https://github.com/leonsmiers)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
https://www.rsm.nl/mba/global-executive-onemba
https://victorzhou.com/blog/intro-to-random-forests/
https://scikit-learn.org/stable/auto_examples/ensemble/plot_forest_importances.html
https://developers.google.com/places/web-service/search#find-place-examples
https://developers.google.com/places/web-service/supported_types

WARNING
The Google APIs are NOT free of usage. See the Google APIs Pricing sheet for the latest pricing.
The Google Cloud Dashboard billing information DOES NOT PROVIDE real time insight in the usage. I found out the hard way there is a lag of (at least) several hours. Officially it even takes 48 hours to settle the bill.
At the current data the pricing was $17 for 1000 Place API calls. In the below code for each Burger King store ±15 calls are executed. In total there are (at current date) 66 Burger King locations in The Netherlands. In total every Burger King location results into ±1000 API calls.
https://cloud.google.com/maps-platform/pricing/sheet/
