# Cleaning your Data in Python Better than Levi Ackerman
If you have ever had to deal with a real world dataset, you know very well how much of a nightmare it is to deal with unclean data. This is why an essential part of the data science workflow pipeline is to first clean the data after gathering it. All manner of problems with datasets can exist: wrong data types, outliers, missing data, misspelled values, non-uniform units, different column names for dataframes to be merged, etc. In this notebook, we will examine some messy data and see how we can try to tidy them up a bit for further analysis.

```
import pandas as pd
df = pd.read_csv('sales_dirty.csv', encoding='utf8')
df.head()
```