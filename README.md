# Data_Analtical_Project-Amazon-Prime-Video-
The Python script is a data analysis project for Amazon Prime Video content. It loads a dataset, cleans and preprocesses the data, engineers new features, and performs exploratory data analysis (EDA) to visualize key insights such as content distribution, genre popularity, temporal trends, and top contributors.
The script is a comprehensive data analysis workflow written in Python using popular libraries like Pandas, NumPy, Matplotlib, and Seaborn. It is designed to analyze a dataset of Amazon Prime Video movies and TV shows. The process is broken down into three main parts:

Setup and Data Loading: The script begins by importing all necessary libraries and then attempts to load the amazon_prime_titles.csv file into a Pandas DataFrame. It includes a try-except block to handle a FileNotFoundError, ensuring the script provides a clear error message if the dataset is not present.

Data Cleaning and Preprocessing: This section focuses on preparing the data for analysis. It fills missing values in the director, cast, and country columns with the string "Unknown". It also converts the date_added column to a proper datetime format and removes any duplicate rows to ensure data integrity.

Feature Engineering and Exploratory Data Analysis (EDA): After cleaning, the script creates two new features: num_genres and num_actors, which count the number of genres and cast members for each title. This is followed by the core EDA, which generates several visualizations to uncover insights:

A pie chart shows the overall distribution of content between movies and TV shows.

A bar chart displays the top 10 most common genres, revealing the platform's content focus.

A line plot illustrates the trend of how many titles were added to the platform each year.

A scatter plot visualizes the relationship between a title's release year and the number of genres it is categorized under.

Finally, bar charts are used to highlight the top 10 directors and actors with the most titles, identifying the most prolific creators and performers on the platform.
