# Movie Review Data Analysis

## Overview
This project aims to analyze movie reviews from The New York Times API and extract movie details from The Movie Database (TMDb) API. The goal is to provide insights into the relationship between movie reviews and their corresponding details such as genre, budget, and revenue.

## Features
- Retrieve movie reviews from The New York Times API based on specific search criteria.
- Extract movie details from The Movie Database API using movie titles obtained from the reviews.
- Merge movie reviews and details into a single dataset for analysis.

## Requirements
- Python 3.x
- Requests library
- Pandas library

## Usage
1. Clone the repository:
    ```
    git clone https://github.com/your_username/movie-review-analysis.git
    ```
2. Navigate to the project directory:
    ```
    cd movie-review-analysis
    ```
3. Install the required libraries:
    ```
    pip install -r requirements.txt
    ```
4. Update API keys:
    - Obtain API keys for The New York Times API and The Movie Database API.
    - Update the variables `nyt_api_key` and `tmdb_api_key` in the code with your API keys.

5. Run the script:
    ```
    python main.py
    ```

6. View the results:
    - The script will generate a CSV file named `merged_data.csv` containing the merged movie review and details dataset.

## Directory Structure


## Credits
- The New York Times API: [https://developer.nytimes.com/](https://developer.nytimes.com/)
- The Movie Database API: [https://www.themoviedb.org/documentation/api](https://www.themoviedb.org/documentation/api)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
