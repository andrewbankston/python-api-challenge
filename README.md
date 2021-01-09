# python-api-challenge

The WeatherPy folder contains the entire set of submission files for the homework: WeatherPy jupyter notebook, VacationPy jupyter notebook, written analysis doc, and output_data folder.

The output_data folder contains saved png files of each graph, a screenshot of the first heatmap without the markers, and a screenshot of the second heatmap with the markers. It also contains the csv file of the initial weather dataframe and the trimmed weather dataframe after removal of "duplicate" cities.

***"duplicate cities": In the initial weather dataframe, I found cities with identical weather conditions and very similar coordinates. Looking deeper, I found that these represented suburbs of the same city (therefore essentially the same city). I decided to remove all but one city in each of these clusters before graphing the data and using it for the VacationPy jupyter notebook.
