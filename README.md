# Website_Ratings

A Flask web app for users to rate and review movies.

## Features

- Add new movies to the database by searching for them using the [The Movie Database API](https://developers.themoviedb.org/3/getting-started/introduction).
- View a list of all movies in the database, including their title, description, year, rating, and review.
- Rate and review movies that are already in the database.
- Delete movies from the database.

## Technologies Used

- Python (version 3.7.10)
- Flask (version 2.0.2)
- HTML
- CSS
- JavaScript
- Bootstrap (version 5.1.0)
- Flask Bootstrap (version 3.3.7.1)
- Flask SQLalchemy (version 2.6.0)
- Flask WTF (version 0.15.1)
- requests (version 2.26.0)

## Getting Started

1. Clone this repository onto your local machine using `git clone <repository-url>` or by downloading the ZIP file.
2. Install the required packages using the command `pip install -r requirements.txt`.
3. Sign up for a free account on [The Movie Database](https://www.themoviedb.org/signup) and generate an API key.
4. In the `main.py` file, replace `"12345"` with your API key on the following line: `MOVIE_DB_API_KEY = "12345"`.
5. Run the command `python main.py` to start the server.
6. Open a web browser and navigate to `http://localhost:5000` to view the app.

## Contributing

This repository is open to contributions from anyone. If you notice a bug or have an idea for a new feature, feel free to submit an issue or a pull request.
