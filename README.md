# Analysis of spending done by House of Representatives members-ProPublica's dataset

This project is based on Members of the House of Representatives spending data hosted by [ProPublica](https://www.propublica.org/datastore/api/propublica-congress-api)

Members of the House of Representatives get an annual budget for their Washington and district offices which cannot be used for personal or campaign expenses. ProPublica publishes spending data on a quarterly basis. I looked at data from 2009-2018.

## Tools used

1- Pandas

2- Numpy

3- Jupyter Notebooks

## Data cleaning

After loading the data, I noticed the following problems with the data:

1- Dates used in the data for different quarters varied in their formats. I formatted these dates in one format so that I can look at data for all quarters together. 

2- Since the data was not standardized, names of PAYEES included duplicates. For instance, "AT&T" might also appear as "A.T.&T." 

3- Some of the datasets contained ‘AMOUNT’ paid by representatives in a string format including commas (e.g. $12,000.65)

## Results

1- Finding mean duration of projects which the payments covered: 30 days

2- Average annual expenditure between Jan 1, 2010 and Dec 31, 2016: $1,223,373,736
Roughly $1 billion budget is allocated to members of House of Representatives to run their affairs.

3- Office with the highest total expenditure in 2016: Government Contributions, which are payments to help out the public. FERS (Federal Employees Retirement System) is the biggest beneficiary of these payments contributing to 21% of total expenditures done by representatives in 2016.
In simpler words,  in 2016 ⅕ of the budget allocated to representatives was used for the purpose of serving civil servant retirees.

4- Highest average staff salary among representatives in 2016: $65,064

5- Percentage of expenditures of the top 20 spenders in 2016 coming from members of the Democratic party: 48.4%
Among top 20 spenders in 2016, 10 belonged to the Democratic and Republican Party each. 
