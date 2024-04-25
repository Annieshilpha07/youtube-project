# YouTube Data Harvesting and Warehousing using SQL and Streamlit

The "YouTube Data Harvesting and Warehousing using SQL and Streamlit" project aims to simplify the collection of data from YouTube channels via the YouTube Data API v3, storing it in a MySQL database, and providing querying capabilities through a Streamlit web interface.

## Technologies Utilized

- **Python**: Primary language for scripting and data processing.
- **Google APIs Client Library for Python**: Used to interact with the YouTube Data API v3 for fetching channel details, playlist details, video details, and comments.
- **Streamlit**: Employs Streamlit to create a user-friendly UI, enabling users to interact with the application, conduct data retrieval, and perform analysis operations.
- **MySQL**: Leveraged for data storage, creating a database for channels, playlists, comments, and videos, and establishing connections with Python.

## Required Libraries

- `googleapiclient.discovery`
- `streamlit`
- `mysql`
- `pandas`
- `regex`

## Features

- **Data Retrieval**: Fetches channel, playlist, comment, and video data from YouTube using the YouTube API.
- **Data Migration and Storage**: Stores data in a SQL database for efficient querying and analysis.
- **Search and Retrieval**: Enables searching and retrieval of data from the SQL database using various search options.

## Usage

1. **Setup**: Install the required libraries using `pip install -r requirements.txt`.
2. **Configuration**: Add your YouTube Data API key to `config.py`.
3. **Run**: Start the Streamlit app using `streamlit run project.py`.

By leveraging these technologies and features, the project streamlines the process of harvesting, warehousing, and querying YouTube data, empowering users with valuable insights and analysis capabilities.

