Simplifying Cancer Treatment
Description

John Cancer Hospital (JCH) is a leading cancer hospital in USA. It specializes in treating breast cancer. Over the last few years, JCH has collected breast cancer data from patients who came for screening/treatment. However, this data has almost 30 attributes, and it is difficult to run and interpret the results. You, as an ML expert, have to reduce the number of attributes
(Dimensionality Reduction) so that the results are meaningful and accurate.

Objective: Reduce the number of attributes/features in data to make the analysis of the results comprehensible to doctors.

Actions to Perform:

    * Use pandas to read data as a dataframe.
    * Check the data. There should be no missing values.
    * Convert the diagnosis column to 1/0 and store in a new column target.
    * Store the encoded column in dataframe and drop the diagnosis column for simplicity.
    * Scale the data so that each feature has a single unit variance.
    * Transform this data to its first 2 principal components.
    * Plot the two dimensions.
    * Print the explained variance.
    * Try the same with 3 principal components.
    * Check the accuracy for 2nd and 3rd components.