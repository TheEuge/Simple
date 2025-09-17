# Simple Project

This is a **"Simple"** project containing a single `index.html` file. The project is simple because it is intended to provide just a small and straight forward testing base for backend/frontend API calling to fetch and process statistical data from YouTube API calls.
The Project is HTML/JavaScript based.

**!ATTENTION!** The Project is NOT recommended for production due to lack of security (API key is explicitly exposed in the code).

## Project Structure
- `index.html`: The main HTML file for the whole project.

## How to Use
Open `index.html` in your web browser to view the project.

## Configuration
No additional configuration files or installing dependencies is required. This project is intended to be minimal and static for fast functionality testing.

## API key
Input your **_real_** YouTube Data API key in the code:

`const API_KEY = 'YOUR_API_key_here'; // Replace with your YouTube Data API key`

- _Development feature_ added: to avoid quota overuse of API data calls download the search request as JSON locally upon a search call by pressing Download button and reuse/modify/amend it for testing UI/frontend part. Just select your locally saved JSON file to load.

## License
MIT License
