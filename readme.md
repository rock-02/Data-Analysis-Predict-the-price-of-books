Course : Exploratory Data Analysis

Course Project : Predict Price of books

Problem Statement(link) : https://machinehack.com/hackathons/predict_the_price_of_books/overview

College : KLE Technological University Hubli

Team Members :      
Tarun S M  –  https://github.com/rock-02  
Sharad C K –  https://github.com/Sharad20-02   
Suresh H B –  https://github.com/Suresh-H-Bhajanthri
      
Overview of the EDA Project:            
The Exploratory Data Analysis (EDA) project aims to predict the prices of books using a comprehensive dataset containing various features, including book titles, authors, editions, customer reviews, ratings, synopses, genres, book categories, and prices. The dataset consists of 6237 records for training and 1560 records for testing, providing ample data for the development of a machine learning model to forecast book prices accurately.

Importance of EDA in Data Analysis:             
Exploratory Data Analysis (EDA) plays a crucial role in the initial stages of data analysis. Its significance lies in the following aspects:

1. Data Understanding: EDA allows us to gain a deep understanding of the dataset by examining its structure, distribution, and characteristics. It helps us identify the types of variables present, their relationships, and potential patterns or trends.

2. Data Cleaning: During EDA, we detect and handle missing data, outliers, and inconsistencies in the dataset. Cleaning the data ensures that the subsequent analysis is based on reliable and accurate information.

3. Feature Selection: EDA aids in selecting relevant features that have a significant impact on the target variable (book prices, in this case). Identifying the most influential features improves the model's predictive power and reduces computational complexity.

4. Relationship Identification: EDA helps uncover correlations and dependencies between variables. Understanding these relationships can provide valuable insights into the factors influencing book prices, such as the impact of author popularity, book genre, and customer reviews.

5. Visualization: Visualizations, such as plots, graphs, and charts, are an essential part of EDA. They offer a clear representation of the data, making it easier to communicate findings and understand complex relationships.
 
The objectives of the course project are as follows:
1. Price Prediction Model: The primary objective of the project is to develop a machine learning model capable of predicting the prices of books based on various features such as book titles, authors, editions, customer reviews, ratings, synopses, genres, and book categories.

2. Data Exploration: Conduct thorough exploratory data analysis (EDA) to gain insights into the dataset, identify patterns, trends, and relationships between book features and prices. This exploration will help understand the data distribution and aid in feature selection.

3. Data Cleaning and Preprocessing: Perform data cleaning to handle missing values, outliers, and inconsistencies in the dataset. Preprocess the data to ensure its quality and suitability for model development.

4. Feature Selection: Select the most relevant and influential features that significantly impact book prices. Employ dimensionality reduction techniques if necessary to reduce computational complexity.

5. Statistical Analysis: Apply appropriate statistical methods and techniques to analyze the relationships between book features and prices. This analysis will provide a deeper understanding of the factors affecting book pricing.

6. Model Building: Develop a robust machine learning model using the selected features and the target variable (book prices). Experiment with various algorithms and techniques to achieve the most accurate price predictions.

Description of the Dataset:     
The dataset used in the course project is a comprehensive collection of information on books, encompassing various attributes that can influence book prices. The dataset consists of 6237 records, which are utilized for training, and 1560 records for testing the machine learning model's performance in predicting book prices. Each record contains the following features:
1. Title: The title of the book.
2. Author: The author(s) of the book.
3. Edition: The edition of the book, including format details (e.g., Paperback, Hardcover) and publication date.
4. Reviews: Customer reviews and feedback about the book.
5. Ratings: The customer ratings given to the book.
6. Synopsis: A brief summary or synopsis of the book's content.
7. Genre: The genre or category to which the book belongs (e.g., Fiction, Mystery, Science Fiction, etc.).
8. BookCategory: The department or section where the book is typically available (e.g., Literature, Science, History).
9. Price: The price of the book (target variable), which is the value we aim to predict using the other features.

Data Collection Process and Sources:          
The data collection process involves gathering information from various sources, such as online bookstores, libraries, and publishing platforms. Automated web scraping tools may have been used to extract data from websites that list books with their respective details.

To collect the dataset, the following steps have been taken:      

1. Identification of Sources: The dataset is available as a CSV file in a downloadable format from https://machinehack.com/hackathons/predict_the_price_of_books/overview. The CSV file contains columns representing different features like Title, Author, Edition, Reviews, Ratings, Synopsis, Genre, BookCategory, and Price.

2. Data Extraction: Import the pandas library and use the `read_csv()` function to load the CSV file and create a DataFrame.

3. Data Preprocessing: Once the data is collected, it undergoes preprocessing to handle missing values, remove duplicates, and standardize data formats. This step ensures the dataset's quality and consistency.

4. Data Split: The dataset is split into two sets: the training set, comprising 6237 records, and the test set, containing 1560 records. This division is essential to evaluate the model's performance on unseen data.

Preprocessing Steps performed:

![Picture1](https://github.com/rock-02/Data-Analysis-Predict-the-price-of-books/assets/98045645/6097724f-3b3b-476a-bc98-22d4d2d7dd29)


Visualize the data through plots, graphs, and charts:

![Picture2](https://github.com/rock-02/Data-Analysis-Predict-the-price-of-books/assets/98045645/8ab9572d-fc47-4ee1-bbe3-c7617423436c)

![Picture3](https://github.com/rock-02/Data-Analysis-Predict-the-price-of-books/assets/98045645/f16adde8-7c46-4d89-ab24-510cce6a26db)

![Picture4](https://github.com/rock-02/Data-Analysis-Predict-the-price-of-books/assets/98045645/b57dff45-9d5f-4f41-96ce-d4903fb56afc)

Process of Selecting Relevant Features:          
The process of selecting relevant features involves identifying the subset of features from the dataset that have the most significant impact on the target variable, which, in this case, is the book price. Here's an outline of the steps in the feature selection process:

1. Initial Feature Exploration: Begin by examining all the features in the dataset and their potential relevance to book prices. Consider features such as author popularity, book ratings, reviews, genre, and edition.

2. Correlation Analysis: Calculate correlation coefficients between each feature and the target variable (book prices). Features with high positive or negative correlations are more likely to be relevant to the price prediction.

![Picture5](https://github.com/rock-02/Data-Analysis-Predict-the-price-of-books/assets/98045645/613c33c4-e3d9-44ec-844b-e90aff6b8a6a)

The rationale behind feature selection is to improve model performance, reduce overfitting, and enhance interpretability. By selecting relevant features, we focus the model's attention on the most influential factors affecting book prices, leading to a more accurate price prediction. Removing irrelevant or redundant features also simplifies the model, making it easier to interpret and understand.

![Picture6](https://github.com/rock-02/Data-Analysis-Predict-the-price-of-books/assets/98045645/36fde674-a445-403b-a43d-34a5d12869ce)


RMSE

![Picture7](https://github.com/rock-02/Data-Analysis-Predict-the-price-of-books/assets/98045645/7f658533-c3e6-4c82-8a13-e7db8d949f2c)

