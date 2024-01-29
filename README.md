## WAtchWave App
---
JavaScript-based web application utilizing the Movie Database (TMDb) API to retrieve and display information about movies and TV shows. 
---
![watch-wave-index](https://github.com/katya-pankov/watch-wave/assets/108332791/e09a0f63-b8be-456a-b23a-9d2700563370)

![watch-wave-movie](https://github.com/katya-pankov/watch-wave/assets/108332791/2d66df9e-4c90-4b35-bf66-99b8239d2bc0)





The codebase is organized into functions that handle specific tasks, such as fetching data from the API, rendering popular movies and shows, and displaying details for individual titles.

The fetchAPIData function is responsible for making asynchronous requests to the TMDb API, abstracting away the details of the API endpoint construction. The project features functions like displayPopularMovies and displayPopularShows that fetch and render popular movies and TV shows, respectively, in the designated sections of the HTML document.

Details pages for movies (displayMovieDetails) and TV shows (displayShowDetails) are dynamically generated based on the unique identifier extracted from the URL parameters. These functions fetch detailed information from the API and construct HTML elements to present the data in a visually appealing manner.

The search functionality (search function) allows users to query the TMDb API based on a specified type (movie or TV show) and search term. The search results are then displayed with pagination using the displaySearchResults and displayPagination functions.

The application incorporates a slider (displaySlider function) utilizing the Swiper library to showcase currently playing movies. The initSwiper function initializes the Swiper instance with responsive breakpoints for different screen sizes.

Furthermore, utility functions like addCommasToNumber are provided to format numerical values with commas, enhancing readability in the user interface.
