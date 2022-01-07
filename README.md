# Dataset-Maker

Download images using [Pexels](https://www.pexels.com/) [API](https://www.pexels.com/pt-br/api/documentation/) and create train and validation lists for machine learning purposes

## Requirements

* Your own Pexels api key (you can get your own from this [link](https://www.pexels.com/pt-br/api/))

## How to use

  Assuming in main folder (Dataset-Maker)

  1. Create json file with name: _api_key_pexels.json_
  
  2. Paste your Pexels api key in the file as a string (ex. "08724077gfcbhe9ye877f434d56hsh9928")

  3. Run command in _linux_ console:

    python build_dataset.py -s [search terms] -n [number of images per search term]
    
    * [search terms] can be any number of terms. (ex. python build_dataset.py -s cats dogs -n 10)
   
   
