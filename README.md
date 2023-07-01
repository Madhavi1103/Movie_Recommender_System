# Movie_Recommender_System
This is a movie recommender system built using Python and Streamlit. It recommends similar movies based on user-selected movies using content-based filtering. The system analyzes the movie's metadata such as genre, keywords, cast, and crew to find similar movies and provide recommendations.

**Requirements:** Python 3.x , Jupyter Notebook , Streamlit , scikit-learn , NumPy , Pandas

**Setup:**
1. Install the required dependencies by running the following command in your terminal or command prompt: -> pip install streamlit , -> 
   pip install scikit-learn , -> pip install numpy , -> pip install pandas
2. Prepare the dataset:
   - Download the TMDB 5000 Movie Dataset from Kaggle.
   - Here is the dataset link:
   - tmdb_5000_movies.csv:-https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv
   - tmdb_5000_credits.csv:-https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_credits.csv
   - Extract the dataset and move the tmdb_5000_movies.csv and tmdb_5000_credits.csv files into the data directory.
3. Place the web_app.py file and the two pickle files (movie_list.pkl and similarity.pkl) in the same directory.

**How to Run:**
1. Open your terminal or command prompt. Navigate to the directory where the files are located. Run the following command: _ streamlit 
   run web_app.py__ The web application will start, and you will be provided with a URL to access the application locally. Open the URL 
   in your web browser.
2. Select a movie from the dropdown menu or type the name of a movie in the input field.
3. Click on the "Recommend" button to get a list of similar movies based on the selected movie.

**Features:**
- Recommends similar movies based on user-selected movies.
- Provides a dropdown menu and input field for easy movie selection.
- Displays the recommended movies along with their titles and posters.

**Contribution:** Contributions to this project are welcome. If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request on the project's GitHub repository.

**License:**
This project is licensed under the MIT License.

**Contact:** For any inquiries or questions, feel free to contact Madhavi Kapil at madhavikapil123@gmail.com.
