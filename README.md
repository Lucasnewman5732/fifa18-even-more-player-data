# A more complete FIFA 18 player dataset

#### Forked from [here](https://github.com/amanthedorkknight/fifa18-all-player-statistics), but this project no longer bears much resemblance to the original.

This repo contains both the dataset and the code used to scrape so-fifa.com.

## Why fork the original project?

1. I wanted more fields. This dataset contains extra fields such as International Reputation, traits and specialities.
2. Efficiency:
    - The original project all takes place in a Jupyter notebook. I've rebuilt the crawler as a Python package.
    - The original project runs synchronously. I can only imagine that this takes several hours.
3. I've stored the data using the .feather format alongside .csv - this is more convenient for Python and R users
4. Fun

## Future improvements:

- There are still a few fields that could be added if anyone wants them, such as contract expiry date.
- Scrapy might speed things up
- Tests
- Building an archive (EA updates its player data regularly and it would be useful to be able to make comparisons between old versions)