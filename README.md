The Netflix dataset contains data from different movies and TV shows. It containts the following information:

 ![download](https://github.com/CPD9/data_cleaning_n_visualization_netflix_dataset/assets/66946145/e7ea4313-58e7-481a-8392-93e32b9f32f9)

To better understand the data contained in the dataframe, we use a set of functions available from pandas, which are summarised as follows:

- `.head()` prints the header of a given dataframe.
- `.dtypes` describes the datatypes of all columns in the dataframe.
- `.info()` provides an overview of the different column data types and missing values in the given dataframe
- `.describe()` returns a distribution of numeric columns in the dataframe
- `.isna().sum()` provides the number of missing values per column in our DataFrame
- `.unique()` retrieves the unique values in a given dataframe column


**Visualisation:**

- `sns.displot()` plots the distribution of one column in your dataframe.

Below are some of the results of the data visualization.

![newplot-4](https://github.com/CPD9/data_cleaning_n_visualization_netflix_dataset/assets/66946145/dd42e6b7-3743-4d55-ac8d-792ed0af786b)

![newplot-5](https://github.com/CPD9/data_cleaning_n_visualization_netflix_dataset/assets/66946145/2f82a23d-7648-4f49-b052-c6576c06b471)

![newplot-6](https://github.com/CPD9/data_cleaning_n_visualization_netflix_dataset/assets/66946145/650cdc75-1c4d-478e-8bf1-5653ff9a9c5a)

![newplot-7](https://github.com/CPD9/data_cleaning_n_visualization_netflix_dataset/assets/66946145/ea013a07-67ba-45e9-9024-b7fc75819d5f)

![Unknown-7](https://github.com/CPD9/data_cleaning_n_visualization_netflix_dataset/assets/66946145/ac64fe98-abf7-4188-925d-c5e36cbc073b)

The last image shows the most frequent words in the shows 'titles'.
