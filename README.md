# Book Recommender System

This project implements a Book Recommender System using both popularity-based and collaborative filtering techniques. The recommender system suggests books to users based on their preferences and similarities with other users.

# Reference 

- [Kaggle Dataset](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)

# Features
- Popularity-Based Recommendations: Recommends popular books to users, regardless of their individual preferences.
- Collaborative Filtering: Utilizes collaborative filtering to recommend books based on similar users' preferences.
- Web Application: Includes a user-friendly web interface for searching books and receiving recommendations.
- Templates: Utilizes HTML templates for the user interface:
  - [index.html](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/templates/index.html): Landing page for the web application.
  - [recommend.html](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/templates/recommend.html): Page displaying recommended books based on user input.
- Application Backend: Utilizes [app.py](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/app.py) as the backend of the web application.
- Pre-trained Models: Includes pre-trained models stored as .pkl files:
- [book.pkl](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/books.pkl): Data file containing information about books.
- [popular.pkl](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/popular.pkl): Pre-calculated popular books for popularity-based recommendations.
- [pt.pkl](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/pt.pkl): Final rating data with no duplicate values.
- [similarity_score.pkl](https://github.com/HarshalShimpi027/Book_Recommender_System/blob/main/similarity_score.pkl): Pre-computed similarity scores for collaborative filtering.

# Usage
1) Clone the repository to your local machine.
2) Ensure you have Python and required dependencies installed.
3) Run app.py to start the web application.
4) Access the web application through your browser and start searching for books and receiving recommendations.

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
