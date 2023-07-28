![image](https://github.com/vardhanreddy369/AnimeSensei-EDA/assets/91843112/50557dc0-f35a-480d-a354-ae3ce225009c)

# **Anime Recommendations Database - Exploratory Data Analysis (EDA)**

This repository contains Python code to perform Exploratory Data Analysis (EDA) on the Anime Recommendations Database. The code explores and analyzes the dataset, providing insights into various attributes of anime.

# **Dataset Overview**

The dataset consists of information on 12,294 anime, including the following attributes:
- anime_id: A unique identifier for each anime.
- name: The full name of the anime.
- genre: A comma-separated list of genres associated with the anime.
- type: The type of the anime, such as TV, Movie, OVA, etc.
- episodes: The number of episodes in the anime (1 for movies).
- rating: The average rating out of 10 for each anime.
- members: The number of community members associated with each anime.

# **Code Description**

The provided Python script "anime_eda.py" performs the following tasks:

## 1.  **Data Loading and Exploration**
   - Loads the "Anime.csv" dataset into a Pandas DataFrame using `pd.read_csv()`.
   - Displays the first few rows of the dataset using `anime_data.head()`.
   - Provides summary statistics of the dataset using `anime_data.describe()`.
   - Checks for missing values in the dataset using `anime_data.isnull().sum()`.

## 2.  **Data Visualization**
   - Utilizes Matplotlib and Seaborn to visualize the data.
   - Plots a histogram to visualize the distribution of anime ratings.
   - Creates a countplot to display the distribution of anime types (e.g., TV, Movie, OVA).
   - Generates a bar plot to show the average rating per anime type.
   - Uses a scatter plot to visualize the correlation between ratings and the number of members.

# **Instructions**

## 1.  Clone this repository to your local machine:

```
git clone <repository_url>
```

## 2.  Navigate to the repository directory:

```
cd AnimeSensei-EDA
```

## 3.  Install the required libraries (NumPy, Pandas, Matplotlib, Seaborn) if you haven't already:

```
pip install numpy pandas matplotlib seaborn
```

## 4.  Run the Python script "anime_eda.py" to perform the EDA:

```
python anime_eda.py
```

## 5.  Observe the output in the terminal, which includes the first few rows of the dataset, summary statistics, and visualizations.

# **Output**

The output of the code provides valuable insights into the Anime Recommendations Database:
![image](https://github.com/vardhanreddy369/AnimeSensei-EDA/assets/91843112/74cefa70-af8e-48da-9662-fce39194fa27)

![image](https://github.com/vardhanreddy369/AnimeSensei-EDA/assets/91843112/bb97b6bb-8f7d-4941-bffa-03430cdd30e7)

![image](https://github.com/vardhanreddy369/AnimeSensei-EDA/assets/91843112/141692d5-13ad-4ae6-8cd7-87f8caf7b4aa)

![image](https://github.com/vardhanreddy369/AnimeSensei-EDA/assets/91843112/765b0951-34cc-41dc-935c-e511cfbe63ad)

- It displays the first few rows of the dataset, allowing users to glimpse the data structure.
- Summary statistics offer an overview of the dataset's numerical attributes, such as average rating and number of members.
- The visualizations present key patterns and trends within the data, including the distribution of anime ratings, types, and the relationship between ratings and the number of members.

# **Note**

Ensure that the dataset file "Anime.csv" is present in the same directory as the Python script "anime_eda.py" before running the code.

# **Dataset Source**

The Anime Recommendations Database is sourced from myanimelist.net API. We acknowledge and appreciate their contribution to this dataset.

For more details about this project and the Anime Recommendations Database, refer to the [GitHub repository]([https://github.com/your_username/AnimeSensei-EDA](https://github.com/vardhanreddy369/AnimeSensei-EDA)).

---
This README.md provides an overview of the project, its purpose, instructions for running the code, and a link to the GitHub repository. Customize it further with additional details or any other information you want to share about your project. Replace "your_username" in the GitHub repository link with your actual GitHub username.
