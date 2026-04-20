# Mapping the Acceleration of Habitat Loss in the Bear River Migratory Bird Refuge 
### The goal of this project was to condense 30 years of NDVI time series data into a single map that highlights when vegetation/water decline occurred. 
I used the shapefile I obtained from USFWS to create a code in Google Earth Engine that collected Landsat data over a 30 year period in that specific area.
I added that data as a mosaic dataset and calculated NDVI from Red and NIR bands.
I used this to create a time series and then used python to created a binary raster for each of my files for Dry or Not Dry where Dry was below .2 (The stress boundary for wetlands).
This allowed me to see areas where vegetation no longer existed around water, demonstrating a decrease in important edge habitat for migratory birds. 
<img width="526" height="405" alt="image" src="https://github.com/user-attachments/assets/062aa364-24b0-43e2-b1ea-0e1f01f654ac" />
I also used the raster calculator tool to calculate the sum of all dry years from 1994-2024 to see which areas were consistently the most dry. I found that areas that were developed were consistently dry, demonstrating human encroachment in habitat.
<img width="675" height="517" alt="image (1)" src="https://github.com/user-attachments/assets/7be52dfb-62d2-4a4b-a1d9-fab711b2a0f8" />
