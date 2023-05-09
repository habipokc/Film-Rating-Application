# Film-Rating-Application

This Flask application provides a film rating platform where users can search for movies, add them to the database, rate and review them, and delete movies from the application. The application utilizes The Movie Database (TMDB) API to retrieve movie information and poster images.

Application Features
  Movie search: Users can search for movies by entering movie titles using the TMDB API.
  Movie addition: Users can add movies they find to the application.
  Movie rating: Users can rate and review the movies they have added.
  Movie deletion: Users can delete movies from the application.
  
Installation and Execution

Installation of Required Libraries:

  Flask: pip install flask
  Flask-Bootstrap: pip install flask-bootstrap
  Flask-SQLAlchemy: pip install flask-sqlalchemy
  Flask-WTF: pip install flask-wtf
  Requests: pip install requests
  
Setting up The Movie Database (TMDB) API Key:

  To obtain a TMDB API key, sign up at https://www.themoviedb.org/ and generate an API key.
  Update the MOVIE_DB_API_KEY variable with the obtained API key.
  
Creation of the Database:

  The application stores movie data in a SQLite database. You need to create a database first.
  Update the app.config['SQLALCHEMY_DATABASE_URI'] variable to specify the path of the database file.
  
Running the Application:

  Navigate to the directory where the application is located in the terminal.
  Start the application by running python app.py or flask run command.
  Access the application by visiting http://localhost:5000 in your browser.
