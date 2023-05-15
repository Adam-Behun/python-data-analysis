# Lesson 1 - python basics

# Lesson 2 - Pandas
- Series
     - 1D labeled array hodling any data type
     - define with: index (axis labels) + data
     - series are better than lists for data analysis
     
- DataFrame
     - 2D labeled data structure with columns of potentially different data type
     - similar to an SQL table
     - define with: index (rowlabels) + data + columns (columnlabels)
     
# Lesson 3
## Loading data from external sources
- read_csv
- read_excel
- read_sql
    - and others
## Explore the dataset
- type("dataset_name")
- head()
- tail()
- info()
- columns
- shape
- index

## Pandas Datatypes (dtype)
- int8, int16, int32, int64 (based on bit size)
- Int8, Int16, Int32, Int64 (can have NULL values)
- float32, float64
- object (any python object)
- bool
- datetime64
- string
- category

## Converting from dtypes
- astype()
- to_numeric/to_datetime()
- read_*(dtype)

## Exporting data
- to_csv
- to_pickle (bytestream) - don't use pkl files if you do not trust the sources