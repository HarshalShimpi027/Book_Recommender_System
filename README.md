# Book Recommender System

This project implements a Book Recommender System using both popularity-based and collaborative filtering techniques. The recommender system suggests books to users based on their preferences and similarities with other users.

# Reference 

- [Kaggle Dataset](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)

# Data Cleaning
- Data cleaning was performed in Google Colab to preprocess the dataset and prepare it for recommendation model training. This included handling missing values, removing duplicates, and ensuring data consistency.
- [Book_Recommender.py](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/book_recommender.py)

# Files
- **Popularity**-Based Recommendations: Recommends popular books to users, regardless of their individual preferences.
- **Collaborative Filtering**: Utilizes collaborative filtering to recommend books based on similar users' preferences.
- **Web Application**: Includes a user-friendly web interface for searching books and receiving recommendations.
- **Templates**: Utilizes HTML templates for the user interface:
  - [index.html](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/templates/index.html): Landing page for the web application.
  - [recommend.html](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/templates/recommend.html): Page displaying recommended books based on user input.
- **Application Backend**: Utilizes [app.py](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/app.py) as the backend of the web application.
- **Pre-trained Models**: Includes pre-trained models stored as .pkl files:
- **[App.py](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/app.py)**: Flask application for serving the web interface and handling recommendation requests.
- **[Index.html](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/templates/index.html)**: HTML template for the home page of the web application.
- **[Recommend.html](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/templates/recommend.html)**: HTML template for displaying recommended books.
- **[Book.pkl](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/books.pkl)**: Pickle file containing book data.
- **[Popular.pkl](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/popular.pkl)**: Pickle file containing popularity-based recommendation data.
- **[Pt.pkl](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/pt.pkl)**: Pickle file containing preprocessed rating data with no duplicates.
- **[Similarity_score.pkl](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/similarity_score.pkl)**: Pickle file containing similarity scores for collaborative filtering.

# Usage
1) Clone the repository to your local machine.
2) Ensure you have Python and required dependencies installed.
3) Run [App.py](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/app.py) to start the web application.
4) Run on Local environment (PyCharm).

# Dependencies
- Python 3.x
- Flask
- Pandas
- NumPy

# SnapShot of WebSite
![Home Page](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/Home%20Page.png)

# Recommend Book Page
- Search for Book '1980' and got the below result
  
![Recommend Book](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/Recommender%20Page.png)

# Credits
This project was developed by Harshal Shimpi as a part of Book Recommend Project. Special thanks to CampusX.[Nitish Singh]
