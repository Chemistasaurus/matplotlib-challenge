# matplotlib-challenge
Imported dependencies.
Set the file paths for both csvs, read the csvs into pandas, and merged the two csvs into one dataframe.
Counted the number of unique values for mouse ID
Found which mouse ID was duplicated, displayed the duplicated mouse ID and cleaned up the dataframe so it did not have the duplicated mouse data.
Verified that the number of mice was reduced by one, meaning the duplicated mouse data was removed.
Found how many different drug regimens were in the dataframe.
Made an empty list to append to.
Stored the unique drug regimens into a variable.
Looped through the cleaned dataframe by drug regimen by first finding the rows where the drug regimen was equal to the current drug regimen we were looking for.
  Then, in the rows with the current drug regimen, take the mean, median, variance,standard deviation, and standed error of the mean for the column "Tumor Volume" and stored those values in variables.
  These variables were appended into the empty list, the list was converted to a dataframe and appropriate column names were added.

  ![image](https://github.com/Chemistasaurus/matplotlib-challenge/assets/132176159/89d5f8fd-6ca1-48c7-8a11-86ad0ba8ab82)

The dataframe was sorted by drug regimen in alphabetical order.

Bar and Pie Charts
Created a bar chart that shows the number of timepoints measured for each drug regimen.

![image](https://github.com/Chemistasaurus/matplotlib-challenge/assets/132176159/b1370cda-4e02-438e-82a8-993acd688fbe)

Created two pie charts that show the proportion of male and female mice in the study.
  pandas plotting

  ![image](https://github.com/Chemistasaurus/matplotlib-challenge/assets/132176159/3c33ab5e-2c4e-4f5f-b1cc-2c428a00d748)

  matplotlib plotting

  ![image](https://github.com/Chemistasaurus/matplotlib-challenge/assets/132176159/03661133-6f81-4c36-ac1f-ca67d67d600e)


  Quartiles, Outliers and Boxplots
  Grouped the cleaned study data by Mouse ID and found the maximum timepoint recorded for each mouse.
  Reset the index to the maximum timepoint.
  Merged the maximum timpepoint data with the clean study data.
  Created a list of drug regimens we want to compile data about and created an empty list to compile all data into.
  Loop through each row in the treatments list and stored the tumor volume value for the location(s) that had the matching drug regimen.
  Appended the empty list with the tumor volume values.
  Commented the formulas to set up the boxplot. At this point, I know that the list that I am appending to does not have the correct data, so moving forward with the boxplot portion was not going to work.

  Line and Scatter Plots
  Created a line plot showing the tumor volume over time of a mouse that was on the Capomulin drug regimen

  ![image](https://github.com/Chemistasaurus/matplotlib-challenge/assets/132176159/53ad939e-401d-4002-90a2-138dead70586)


  Created a scatterplot showing correlation between mouse weight and average tumor volume.
    Displayed the linear regression line and the correlation coefficient.

    ![image](https://github.com/Chemistasaurus/matplotlib-challenge/assets/132176159/bcb3ffcb-31b6-4adc-a4eb-608f2b7a8a17).


  I will work on the boxplot section once I have more time to figure out what I am doing wrong.




