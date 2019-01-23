# R-Shiny
Diamond Data: https://www.dropbox.com/s/ipdff06edkjlotz/diamonds.txt?dl=1

In this assignment, I am asked to create a Shiny app with the following features:
1. A fileInput to let the users upload a tab separated file of data. 
2. Render the data using DT::dataTableOutput and a histogram of the carat column.
3. A slider that automatically subseta the data, updatethe DataTable and the histogram. (range from 1 to the number of rows in the dataset on the slider).
4. An actionButton that resets the subsetted data back to the full dataset.
