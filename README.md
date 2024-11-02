# Exploring local Points of Interest in OpenStreetMap

## Examples using Overpass, Python, and Pandas

Some bits and pieces of Python code that I wrote to query OpenStreetMap Points of Interest using the
[Overpass API Python wrapper](https://github.com/mvexel/overpass-api-python-wrapper), and to investigate the POIs using Pandas.

These queries provided the numbers behind a series of entries about POI mapping in [my OpenStreetMap Diary](https://www.openstreetmap.org/user/alan_gr/diary), starting with [this entry](https://www.openstreetmap.org/user/alan_gr/diary/405425).

The code was written for a very specific purpose, but there may be some useful ideas for anyone else who wants to explore OpenStreetMap through Python. Please note that it focuses on detailed analysis of POIs in a relatively small area (currently about 400 points), and is not intended for use over large geographical areas.

So fare there are two Jupyter notebooks:

[Exploring local POI data at a single point in time](<1 Explore current local POI data.ipynb>)

[Exploring changes in POI data between two points in time](<2 Explore changes in local POI data.ipynb>)

I am working on a Python script to tidy up the Notebook code and make it more suitable for repeated use.