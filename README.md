# 2016 Election Map

![Alt Text] https://github.com/magnesium-nitrate/election-visuals-2016/edit/master/contin-map.gif

## About the code
* I took the 2016 election data and created a map that shows how democrat or republican a certain county is
* Counties that are more red are more republican while counties that are more blue are more democrat
* Counties that are purple are an even mix of both
* To get an accurate representation about how certain counties lean politically, I removed all third party votes from the original dataset

## Running the code yourself
* Download the electionmap2016.ipynb and open it in google colab
* Functions that are needed to run the code are included in the !pip install statements
* The data is in genelc2016.csv and you can find the original csv file at https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/VOQCHQ

## Viewing the Map
* You can download the map as a png file or as an interactive html file
* To view the attached html file, downlaod the file and view it in your desired browser

## Possible Errors
* Google colab can sometimes stop printing the map (usually the error goes "geojson has no attribute called counties")
* To fix this error, create a new colab notebook and copy paste the code and the error should go away
