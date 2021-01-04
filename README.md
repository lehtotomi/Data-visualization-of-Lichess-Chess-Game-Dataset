# Data-visualization-of-Lichess-Chess-Game-Dataset
Data visualization of Lichess Chess Game Dataset

The dataset used is from https://www.kaggle.com/datasnaek/chess?select=games.csv
and is Licensed under CC0: Public Domain. 


provides funtions:

plot_totals(top)
plots bar chart of n most played general openings, where top=n and the total count of games played are show on the y-axis.

plot_percents(top)
plots bar chart of n most played general openings, where top=n and the total count of games played are show on the y-axis.

get_total_and_percent_by_name(name)
returns total count and percentage of the general opening in which the given opening belongs.


and helper functions:

isIterable(x)
returns True if x is iterable, False otherwise

alltoList(r)
checks if the element of the given list is iterable. If not list containing the element replaces the element in the original list.

to_df()
returns the chess dataset in dataframe format.

topOpeningsByCount(top)
returns Pandas series containing n most played general openings and total times these opening where played, where n=top.

TopByPercent(top)
returns Pandas series containing n most played general openings and total percentage these opening where played, where n=top.


