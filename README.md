# Toronto Neighborhood Analysis

## Overview
This project delves into Toronto's neighborhood data, aiming to uncover insights into the city's diverse areas. By leveraging postal code information and Foursquare API data, the project clusters neighborhoods based on venue categories, providing a nuanced understanding of Toronto's cultural and commercial landscape.

## Installation
Ensure you have the necessary dependencies installed to run the project:
- numpy
- pandas
- geopy
- requests
- BeautifulSoup
- folium
- scikit-learn
- matplotlib

## Install dependencies using pip:
```python
pip install numpy pandas geopy requests beautifulsoup4 folium scikit-learn matplotlib
```
## Usage
- Run Neighbourhoods_in_Toronto_1.py to retrieve postal code data from Wikipedia and store it as toronto.csv.
- Execute Neighbourhoods_in_Toronto_2.py to fetch venue information for each neighborhood using Foursquare API.
- Utilize Neighbourhoods_in_Toronto_3.py to perform k-means clustering based on venue categories and visualize clusters on a map using Folium.

## Example

Execute the following commands:
```python
python Neighbourhoods_in_Toronto_1.py
python Neighbourhoods_in_Toronto_2.py
python Neighbourhoods_in_Toronto_3.py
```

## License
This project is licensed under the MIT License. See the LICENSE file for details.
