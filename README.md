# Movie Analysis
This project evaluates movies by criteria relating to gender.

## Abstract  
Our goal is to create an app that displays gender information about movies. For example, a user may want to know how socially conscious the movie Toy Story is. The app prompts the user to type in the name of the movie, and then returns information about the movie which includes: movie title, release year, short synopsis, Bechdel test scores, explanation of the test scores, % of cast that are women. Our dataset contains over 17,000 movies, although not all fields are available for all movies.

## Instructions  
To use the application, download cleanedMovieDataFinal and menu_final to the same folder. As you run menu_final, you will receive specific instructions on how to enter a movie name. Once you have selected a movie, you can choose one of the following options:  

    1. See Bechdel Test scores.
    2. See cast gender information
    3. See crew gender information
    4. See summary of gender statistics across all movies
    5. Enter a different movie name



## Structure  
In addition to the menu code and final CSV mentioned above, this Repo contains the following folders:    

-DOCS:  
This contains basic info about the project, including a spreadsheet that we used for planning along with the professor's instructions.


DATA PROCESSING:  
This contains our group's work to create the final CSV. Python files include the following:  
1. mastercode.py: this initial code combines the Kaggle and scraping work. It generates movietests_20200227_v2.csv.  
2. api_dataframe_merge.py: adds synopsis data from the API. It outputs all of the CSV files starting cleanedMovieData and ending with numbers.  
3. merge_cleaned_movieDF.py: Merges the 7 files starting with cleanedMovieData and creates cleanedMovieDataFinal.csv.  

Everyone also has an individual branch containing the original work that they sent via email as of 2.26.20.

## Data  
Original sources for the project are listed below:  
CSV files: https://www.kaggle.com/rounakbanik/the-movies-dataset  
Web scraping: https://bechdeltest.com/  
API work: https://developers.themoviedb.org/3/getting-started/introduction  
Note: since the CSV files were too large to be uploaded to GitHub, they are saved on Gootle Drive here: https://drive.google.com/drive/folders/1YBz5KyT-jH_OTG0yfxhmN35hdNdsBP5V?usp=sharing.
