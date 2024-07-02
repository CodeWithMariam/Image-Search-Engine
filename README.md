# Image Search Engine

An image search engine that uses the Unsplash API to fetch and display images based on user queries. This project allows users to search for images and view them directly from the Unsplash website.

## Features

- **Search Images:** Users can search for images by entering keywords.
- **View More Results:** Users can load more results by clicking the "Show More" button.
- **Direct Links:** Each image links directly to its source on Unsplash.

## Technologies Used

- HTML
- CSS
- JavaScript
- Unsplash API

## How to Use

1. Clone the Repository:
   ```bash
   git clone https://github.com/CodeWithMariam/image-search-engine.git
2. Navigate to the Project Directory:

   cd image-search-engine
3. Open index.html in Your Browser:
Simply open the index.html file in your preferred web browser to start using the image search engine.

## Code Overview
### HTML
The HTML file contains a form for user input, a section to display search results, and a button to load more results.

### CSS
The CSS file contains styles to ensure the application is visually appealing and user-friendly.

### JavaScript
The JavaScript file handles the functionality of the search engine, including:

- Fetching data from the Unsplash API
- Displaying search results
- Handling pagination for more results
#### Key JavaScript Functions
searchImages(): Fetches images from the Unsplash API based on user input and displays them.
Event Listeners: Listens for form submission and "Show More" button clicks to fetch and display additional results.
## API Key
To use this project, you need an Unsplash API key. Replace the placeholder API key in the JavaScript file with your own Unsplash API key:
const accessKey = "YOUR_UNSPLASH_API_KEY";

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.