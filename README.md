# CFBScrapy
Python wrapper for the collegefootballapi located here: https://api.collegefootballdata.com/api/docs/?url=/api-docs.json#/

## Installation

Can be installed using PyPi using pip install CFBScrapy

## Usage

```python
from CFBScrapy import cfbtools
t = cfbtools.get_game_info(year=2018)
```


## Contributing

Feel free to open any issues or pull requests. Additionally, you can reach out to me at ryan.lindholm@outlook.com with any questions or concerns.

## Roadmap

1. Scraping 247 player rankings to get the individual player rankings
2. EPA and Win probability a la nflscrapR
3. Normalization of the tables returned

Created by Ryan Lindholm
