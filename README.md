# Command/Operation used for Data-Preprocessing 
## I/O 
- "r"   Opens a file for reading only.
- "r+"  Opens a file for both reading and writing.
- "rb"  Opens a file for reading only in binary format.
- "rb+" Opens a file for both reading and writing in binary format.
- "w"   Opens a file for writing only.
- "a"   Open for writing.  The file is created if it does not exist.
- "a+"  Open for reading and writing.  The file is created if it does not exist.


# Pandas - Data analysis library 
## Pandas 
- pd.read_csv(path_to_csv) - to read csv
- pd.to_csv(column1: values, column2:values) - dataframe to csv
- pd.to_datetime(column_name, format=) - to data/time format
- pd.merge(left,right,how=,on=) - join two tables
- pd.factorize - encode the object in order of occurance
- pd.get_dummies - returns encoded ordinal data 
- pd.scatter_matrix(df) - plots all the combinations of scatter plots

## Dataframe 
- df.loc(columns/labels) - get rows with defined labels
- df.iloc(index) - get rows with defined index
- df.groupby(column) - group rows with similar labels
- df.head(count) - displays top 5 rows if index not defined
- df.reset_index(column) - reset the index of the DataFrame
- df.isnull - returns true if df contains null values
- df.iterrows() - itereates over df, returns index and column names
- df.dtypes - returns the datatype of each column
- df.info() - prints index dtype, columns, non-null values, memory usage
- df.describe() - returns statistics of dataframe




# Numpy - Linear alegrba library 
## Numpy 
- np.var(array/column, axis=) - calculates variance along specifies axis
- np.percentile(x, [1,100]) - returns x with clipped values

# Matplotlib - Data visualization library

# Tsne - Used for dimensionality reduction

# Sklearn - ML algorithms library
## Sklearn
- sklearn.preprocessing.LabelEncoder - encoding categorical data
- sklearn.preprocessing.OneHotEncoder - encoding ordinal data
- sklearn.feature_extraction.text.CountVectorizer - for bag of words implementation
- sklearn.feature_extraction.text.TfidfVectorizer - for term frequency and inverse document frequency

## Scipy
- scipy.stats.rankdata - used for rank transformation
