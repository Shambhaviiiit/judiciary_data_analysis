# Judiciary_data_analysis
Data insights of a data set of all district courts of India
# README
- All codes written for analyzing the given dataset are present in the notebook Data_analysis.ipynb uploaded to the git repository.
- Codes for the classification problem are in notebook Classification.ipynb
- Language used: Python
- Libraries used: Dask, matplotlib, NumPy, sklearn

## Court Data Analysis and Report
### Dispute Types Analysis 
    Analysis of number of cases under each dispute.

Majorly categorised as:

- Withdrawn
- Acquitted
- Dismissed
- Disposed
- Referred to Lok Sabha

From the given disp_name_key file, determined the percentage of cases under each of the above major categories per year.
Visualised the above tabulated data to get a picture of the composition of cases.

The graph obtained shows a substantial decrease in the percentage of cases dismissed as well as acquitted from 2012 to 2018.

Percentage of cases withdrawn and cases disposed has not altered much.


### Number of Cases Registered (State-wise)
    Analysis of the least number of cases registered in a state over the years.

Per state total number of cases filed per year were derived from cases_[year] documents.  
Result shows that while Sikkim registered least number of cases in 2010, Jammu Kashmir has registered the least number of cases from every year thereafter.

From the graph derived, we see that the total number of cases registered in Jammu Kashmir has substantially increased from 3 in 2011 to 58 in 2015.

### Days Taken to Conclude a Case
    Attempted to analyse the duration taken per case to reach to a conclusion, and to see if the duration has witnessed any changes along the years.
    

### Judge Transfer
    A list of all the cases that have had a change in judge between the trials.

### Female Petitioners
    Percentage of female petitioners filing cases in various courts.

Determined the percentage of female petitioners filing cases. The data has many missing entries regarding gender identity of petitioners.

The percentages as plotted were observed to be in the range of 15% to 16% over the 6 years. 

A nearly steady graph, indicating that not much improvement has been seen in the women filing cases for their rights.
