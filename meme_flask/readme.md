# Meme Flask Website

This is a simple Flask-based web application that fetches and displays random memes from various subreddits using the [Meme API](https://meme-api.com/). The website automatically refreshes every 30 seconds to show a new meme.

## Features

- Fetches random memes from the Meme API.
- Displays the meme image along with the subreddit it originated from.
- Automatically refreshes the page every 30 seconds to show a new meme.

## Requirements

- Python 3.x
- Flask
- Requests

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/meme-flask.git
   cd meme-flask
2. **Set up a virtual environment (optional but recommended):**
 `python3 -m venv venv
  source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. **Install the required dependencies:**
   `pip install Flask requests`
4. **Run the Flask application:**
  `python3 meme_flask.py`
5. **Open your web browser and navigate to:**
   `http://127.0.0.1:5000/`
