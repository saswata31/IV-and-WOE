# IV-and-WOE
This code calculates Information Value (IV) and Weight of Evidence (WOE) of an input Data Frame in python. This code can take both continuous and categorical variables from input object to calculate WOE and IV. While binning options are available for continuous variables, which essentially allows the user to control number of bins, for categorical variables, this code block creates fixed numbers of bins based on number of levels present in that variable + 1 bin for missing values. This code can successfully handle missing values or NaN issues present in any real life data. Hence no such data cleaning is required prior to this.
