# ETL pipeline from World Bank Open Data

Data pipeline to extract data from the  World Bank Open Data, specifically from the following indicators: 

* Rural Population
* Access to electricity, rural (% of rural population)

through this program, we will transform the data from the World Bank API (clean, reshape and merge the indicators) and load it to a database

The output data shows the correlation between the growth of the rural population and its access to electricity from 2000 to 2020



## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the libraries

```python
pip install -r requirements.txt

```
Set your environment variables to load the data to your database, or change the code and save it as a CSV


