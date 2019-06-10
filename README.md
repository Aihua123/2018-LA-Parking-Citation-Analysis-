# 2018 LA Parking Citation Analysis
Analysis At a Glance: https://aihua123.github.io/New_LA/index.html

# Project Overview

The dashboard helps user to understand where the most tickets are being issued, what are the most frequent violations, where parking fines go, and peak violation times and months. The dataset used for this analysis is hosted by the city of Los Angeles.

# Project Approach

Used Pandas in a Jupyter Notebook to create and cleanup data. Converted the data into year and split the data per year. Created the right date format and time format using Python/Pandas. Once dates were cleaned up and formatted, a separate CSV file for 2018 and previous years were created. In the original dataset, coordinates were provided in ESPG California state plane format and had to be converted to decimal degree Latitude and Longitude for plotting. Then the tables were merged in to one master table. Used Google API to get the maps and create heat maps. 
