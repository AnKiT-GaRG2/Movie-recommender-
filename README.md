# Movie Recommender System

## Overview
The Movie Recommender System is a web application that suggests movies to users based on their preferences. It utilizes a machine learning model to analyze movie similarities and fetches movie posters from an external API.

## Features
- User-friendly interface built with Streamlit
- Movie recommendations based on user-selected movies
- Fetches movie posters from The Movie Database (TMDB) API
- Error handling for API requests

## Installation

1. Clone the repository:
   ```
   git clone 
   cd movie-recommender-system
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Create a `.env` file in the root directory and add your TMDB API key:
   ```
   TMDB_API_KEY=your_api_key_here
   ```

## Usage
Run the application using Streamlit:
```
streamlit run src/app.py
```

Open your web browser and go to `http://localhost:8501` to access the application.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
