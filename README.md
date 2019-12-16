# ggplottutorial-
Python and R are some of the most popular languages for machine learning. 
For someone switching to Python from R, can they continue using the plotting tools from R? 
Yes! With the package plotnine, which allows the functionality of ggplot from R. 
Python used to have a ggplot package, but it is no longer functional (it appears that some of the dependencies are no longer maintained). 

1. pip install plotnine
2. basic layout of plotnine formulas:
(ggplot(data) + aes(x = x, y = y) + geom_graphtype(size=20))
3. Get creative! I tried several types of graphs and everything from R's ggplot2 library seemed to work with plotnine.
