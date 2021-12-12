# IV-and-WOE
1. This calculates Information Value (IV) and Weight of Evidence (WOE) of an input Data Frame in python. This can take both continuous and categorical variables from input object to calculate WOE and IV. While binning options are available for continuous variables which essentially allows the user to control number of bins, for categorical variables this creates fixed numbers of bins based on number of levels present in that variable + 1 bin for missing values. This code can successfully handle missing values or NaN issues present in any real life data. Hence no such data cleaning is required prior to deploying this.


2. This code creates an individual xlsx sheet for every variable it has in input-X dataframe. 


3. Iteratively it puts the output for a same variable in a single xl-sheet. For eg. if for var_1, 10 bins are created, then iteratively it would create bins starting from 10 to 3, and put the results for each iteration ( from 10 to 3) in the sheet named "var_1". Hence a total 8 tables would be appended back to back in the same output sheet.


4. The user needs to change the path of the location where the output file thus created would be saved.
################################
