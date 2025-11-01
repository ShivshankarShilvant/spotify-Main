# Spotify - Web Player: Music for everyone

This project is a web-based Spotify-inspired music player built using HTML, CSS, and JavaScript. It allows users to browse playlists, view albums, and play music directly from the browser with a responsive and modern interface.

## Features

- Browse and play songs from different albums and playlists
- Responsive UI inspired by Spotify’s web player
- Interactive play bar with seek and volume control
- Dynamic playlist and album display loaded from local folders
- Smooth transitions and mobile-friendly design

## Project Structure

- `index.html`: Main HTML file for the web player UI
- `css/`: Contains `style.css` and `utility.css` for styling and layout
- `js/app.js`: Handles the logic for loading songs, albums, and player controls
- `songs/`: Directory for storing music files and album information (each album should include an `info.json` and cover image)
- `img/`: Contains icons and images used in the UI

## Getting Started

1. Clone the repository.
2. Add your MP3 files inside the `songs/` directory, organized by album folders. Each album folder should include an `info.json` with album metadata and a `cover.jpg` for the album art.
3. Open `index.html` in your browser.
4. Enjoy music playback with a Spotify-like experience!

## Example Album `info.json`

```json
{
    "title": "Copyright Songs",
    "description": "Cover Songs for you"
}
```

## Credits

- UI inspired by [Spotify](https://spotify.com)
- Icons and assets from [Spotify assets](https://developer.spotify.com/documentation/design/)

## License

This project is for educational purposes and is not affiliated with Spotify.
