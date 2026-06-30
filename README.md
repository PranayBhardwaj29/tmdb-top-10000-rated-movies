# TMDB Top 10,000 Rated Movies Dataset

A dataset containing the top 10,000 highest-rated movies from TMDB (The Movie Database), collected using the TMDB API.

## Dataset

The dataset includes information such as:

- Movie ID
- Title
- Release Date
- Vote Average
- Vote Count
- Popularity
- Overview


## Data Source

Data was collected using the official TMDB API.

https://developer.themoviedb.org/

## Usage

1. Create a TMDB API key.
2. Add your API key.
3. Run

The script will fetch movie data and save it as a CSV file.

## Notes

- Movies are retrieved from TMDB's discover endpoint sorted by rating.
- API rate limits should be respected during collection.


## Acknowledgements

- TMDB API
- Python
- Google Colab
- Pandas
