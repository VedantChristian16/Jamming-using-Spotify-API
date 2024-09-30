# Jamming App - React Project Overview

The Jamming App is a basic music playlist manager that integrates with the Spotify API, allowing users to search for tracks, create custom playlists, and save them directly to their Spotify accounts. This app enables users to log in with their Spotify credentials, search for songs by title or artist, add or remove tracks from a playlist, name their playlist, and save it seamlessly.

This project is part of an offline challenge from Codecademy's Full Stack Web Development path.

## Project Structure

The project is organized as follows:

- **`/src` Folder**: 
  - **`/components`**: Contains all component files, including `.js` files for React components, `.css` files for styling, and image or icon assets.
  - **`/mock`**: Contains mock data used to build the app before integrating the Spotify API.
  - **`/util`**: Contains utility files that manage the connection to the Spotify API and related methods.

## Component Breakdown

The app is composed of several key components:

- **App.js**: The main component, responsible for handling the primary logic, state management, and rendering of child components.
- **SearchResults.js**: Displays the user's name, includes the search bar for querying songs or artists, and renders the search results through the Tracklist component.
- **SearchBar.js**: Provides the input field where users enter song titles or artist names and initiate searches.
- **Playlist.js**: Displays the user’s custom playlist and allows tracks to be added or removed. It includes an input field for naming the playlist.
- **Tracklist.js**: Used in both the SearchResults and Playlist components to render lists of tracks from the search results or the current playlist.
- **Track.js**: Renders individual track information, including the song title, artist, album, and cover art. It also includes an add/remove button for managing playlist tracks.

## Key Features

- **Spotify Login**: Users can log in using their Spotify credentials with a single click.
- **Dashboard Interface**: The app provides a simple dashboard with two main sections: one for managing searches and another for playlist management.
- **Personalized Greeting**: The app greets users by name.
- **Search Functionality**: Users can search for songs by title or artist name.
- **Scrollable Results**: Search results are displayed in a scrollable section, ensuring a smooth user experience.
- **Track Details**: Each track is displayed in a card with relevant details (song title, artist, album, and album cover), along with a button to add or remove tracks from the playlist.
- **Playlist Management**: Users can name their playlists and add/remove tracks easily. The playlist section is also scrollable.
- **Save to Spotify**: Playlists can be saved directly to the user's Spotify account with one click, resetting the playlist section afterward.

## Technologies Used

- Visual Studio Code (VSC)
- GitHub (for version control and repository management)
- HTML, CSS, JavaScript
- React.js (for front-end development)

This project demonstrates key concepts in React development, including component-based architecture, state management, and API integration.
