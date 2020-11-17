# CMPE256SteamRecSys
Recommendation System for Steam Games

Raw Data: https://cseweb.ucsd.edu/~jmcauley/datasets.html#steam_data

To run model:
1. Download the [data](https://cseweb.ucsd.edu/~jmcauley/datasets.html#steam_data) into data folder or uncompress the dataset in data folder
2. Installed libraries if not installed:
Sklearn: pip install -U scikit-learn
Surprise: pip install scikit-surprise
LightFM: pip install lightfm
3. Run notebooks:
	- Run fix_json.ipynb in notebooks to fix the json file
	- Run preprocessig noteboooks to process data and save processed data to .csv: ImplicitRatingToCsv.ipynb, process_games_id_name_pair.ipynb, process_games_metadata.ipynb, popularity_recsys.ipynb
