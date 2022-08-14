# Neural Net Classifier

A case study of different approaches to a simple classifier. Trying different pre-trained layers while tweaking some parametres to reach a high accuracy.

## Classes
  - Challenger Tank
  - Tangerine
  - Pineapple

## Data
* The data for this project was scraped from the web using closed source web scraper. Will need to include that functionality as a wip 
* Directory Structure

```
    |-- test
        |-- challengertank
        |-- tangerine
        |-- pineapple
    |-- train
        |-- challengertank
        |-- tangerine
        |-- pineapple
    |-- val
        |-- challengertank
        |-- tangerine
        |-- pineapple
```


_Recommended to use [venv](https://gist.github.com/Geoyi/d9fab4f609e9f75941946be45000632b)_


# Usage
1. `pip3 install -U jupyter matplotlib numpy pandas scipy scikit-learn seaborn tensorflow` || `python3 -m pip install -U jupyter matplotlib numpy pandas scipy scikit-learn seaborn tensorflow`
  * Had a couple of version issues that I had to manually resolve here. Take note of the pip errors.
2. Verify install with ` python3 -c "import jupyter, matplotlib, numpy, pandas, scipy, sklearn, seaborn tensorflow"`. No errors should display.
3. run `jupyter notebook`. Open link if not automatic
