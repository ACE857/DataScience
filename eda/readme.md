When the data is received, I go to EDA (this is the first step), which I perform according to the following algorithm:

    I load data, study the dimension (how many rows and columns are in the data).
    I look to see if the data types are the same (for example, dates are represented by a date, not a string) and change the data to the correct type.
    I look at measures of the central trend (I look at averages, distribution type, range, minimum and - maximum values, standard deviation, negative values, etc.).
    I check the data for the absence of values ​​(delete or fill, depending on the selected method).
    I am studying a time series (checking if the time series is interrupted, if any dates are missing, etc.).
    I work with categorical variables (check the spelling of strings, duplicates, standardize names if necessary).

When the data is ready, I move on to generating the aggregated data (second step) answering my questions (concatenating tables, grouping data, creating new functions, etc.).

When all the data is ready, it's time to visualize and write the story (third step). In my work, I use the Plotly library. With it, you can customize very cool and interactive graphics. Here I would like to stop and pay attention to two types of charts - pie charts (if more than 2 variables to compare) and area charts. I try not to use visualization data, because the human brain is not good at comparing areas (imagine you have a pie chart divided into three areas 34, 33 and 32%, how to visually understand which part is larger?). I recommend replacing the visualization data with a bar chart.

Let's continue. Once we've got the data and decided on the graphs, it's time to move on to writing history. Of course, not all work involves writing a story, but I want to convey this idea.

When writing a story, I recommend:

    The first is to come up with a story. Don't just prepare a description of the diagrams, but add a literary style to the description.
    For example, we can say that on the graph we can see which musical genres were most in demand in China in 2020, or we can say that during our trip to China in 2020, we studied the tastes of the population and found that most of the Chinese in 2020 listened. ..

    The second recommendation, the graphs should be consistently lined up, looking at them, we saw the story, but only individual visualizations.

    And third, and most importantly, all graphs should be described in detail.
