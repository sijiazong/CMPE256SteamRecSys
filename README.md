# CMPE256SteamRecSys
Recommendation System for Steam Games

Raw Data: https://cseweb.ucsd.edu/~jmcauley/datasets.html#steam_data

Preparation to run any notebook:

1. Download the [data](https://cseweb.ucsd.edu/~jmcauley/datasets.html#steam_data) into data folder or uncompress the raw\_data.zip and fixed\_data.zip into data folder.(The files are zipped because GitHub has a strict file limit of 100MB)
2. Installed libraries if not installed:
	- Sklearn: pip install -U scikit-learn
	- Surprise: pip install scikit-surprise
	- LightFM: pip install lightfm

Run notebooks:

1. Run fix_json.ipynb in notebooks to fix the json file
2. Run preprocessig noteboooks to process data and save processed data to .csv:
	- ImplicitRatingToCsv.ipynb
	- process\_games\_id\_name\_pair.ipynb
	- process\_games\_metadata.ipynb
	- popularity\_recsys.ipynb
3. Run model notebooks
	- itemBasedRecommendation.ipynb
	- hybrid recommendations_LightFM.ipynb
4. Run final mode notebook: 
   - final model recommendations.ipynb