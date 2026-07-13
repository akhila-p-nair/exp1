Aim

To load a housing dataset using the Pandas library and perform basic data analysis by displaying the dataset, examining its structure, viewing selected columns, generating descriptive statistics, and visualizing the relationship between total rooms and median house value using a scatter plot.

Theory

Pandas is a powerful Python library used for data manipulation and analysis. It provides the DataFrame, a two-dimensional data structure that stores data in rows and columns. A DataFrame allows users to efficiently read, organize, filter, and analyze large datasets.

NumPy is used for numerical computations and array operations, while Matplotlib is a plotting library used to create charts and graphs for data visualization.

In this experiment:

The housing dataset is loaded into a DataFrame.
The shape, column names, and sample records are examined.
Descriptive statistics such as mean, minimum, maximum, and standard deviation are generated using the describe() function.
A scatter plot is created to visualize the relationship between Total Rooms and Median House Value, helping to identify trends and patterns in the data.
Algorithm
Import the NumPy, Pandas, and Matplotlib libraries.
Load the housing.csv dataset using pd.read_csv().
Display the dataset.
Print the shape of the dataset.
Display the first and last 10 records.
Print the column names.
Display the total_rooms column.
Select the first 150 records of total_rooms and median_house_value.
Plot a scatter graph between total_rooms and median_house_value.
Display the descriptive statistics of the dataset using describe().
Result

The housing dataset was successfully loaded and analyzed. The dataset's structure, sample records, and descriptive statistics were displayed, and a scatter plot illustrating the relationship between Total Rooms and Median House Value was generated successfully.
