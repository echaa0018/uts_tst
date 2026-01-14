# Anime Explorer

A simple, responsive web application to browse top-rated anime, watch trailers, and view image galleries. It runs entirely in the browser using HTML, JavaScript, and Tailwind CSS.

## Data Sources

* **Jikan API:** Anime data and rankings.
* **YouTube Data API:** Official trailers.
* **TMDB API:** High-resolution background images.

## Setup Instructions

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/echaa0018/uts_tst.git
    cd uts_tst
    ```

2.  **Create the configuration file:**
    Create a file named `config.js` in the root directory.

3.  **Add your API keys:**
    Paste the following code into `config.js` and insert your own keys:
    ```javascript
    const CONFIG = {
        YOUTUBE_API_KEY: 'YOUR_YOUTUBE_KEY',
        TMDB_API_KEY: 'YOUR_TMDB_KEY'
    };
    ```

4.  **Run the app:**
    Simply open `mal_top_10.html` in your web browser.