# I310D
Project Goal:

The goal of this project is to curate data by extracting, transforming, loading, plotting, visualizing, and analyzing data on cities in the United Kingdom (UK) from the Wikipedia page "List of cities in the United Kingdom" and performing data visualization and analysis.

For data curation, I specifically extracted and cleaned data from the Wikipedia page to create a structured dataset of UK cities, including attributes like Image,	City,	Year granted or confirmed,	City council status,	Nation/region	City, Population. I took out the image becausew it could not be seen anyways and that data was not necessary or transferrable.

For visualizing the curated data, I wanted to gain insights into the population distribution among UK cities. The best graph to visualize the data is a bar graph for compasion because it is not a trend but rather comparing population between cities. The bar chart also helps me understand the difference in population in UK cities from highest to lowest populations.

Data Sources:

"List of cities in the United Kingdom," accessed at https://en.wikipedia.org/wiki/List_of_cities_in_the_United_Kingdom.

License:

The data extracted from Wikipedia is available under the Creative Commons Attribution-ShareAlike License (CC BY-SA). Users are required to attribute the source and share any derivative works under the same license.

Data Attributes:

The dataset consists of the following attributes:

Image (taken out): Image of the United Kingdom city. 
City: (string object) The name of the city in the United Kingdom.
Year granted or confirmed: (string object): Year at the time.
City council status: (string object) 
Nation/region: (string object) The administrative region or area where the city is located (e.g., England, Scotland, Wales, or Northern Ireland).
City Population: (float) The population of the city at a specific point in time.

Known issues:
Data can be inaccurate on Wikipedia pages since it can be edited by any user, and the data is not always up-to-date or accurate in general. It's important to verify the data and cross-reference it with reliable sources.
The Wikipedia page may have specific criteria for including cities which means that some towns or settlements may be excluded.

To address these potential issues, it's important to carefully validate and clean the data, consider the data's source, and be aware of its limitations when performing analysis and visualization.

