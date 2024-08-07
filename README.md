# Simple Resume Project

## Project Description
This project is a simple two-page résumé created using HTML5 and CSS3. It includes:
- A main résumé page with personal details, experience, education, and skills.
- A contact page with a form and a map showing the person's location using OpenStreetMap.

## Files in the Repository
- `index.html`: Contains the résumé.
- `contact.html`: Contains the contact form and the map.
- `styles.css`: Styles both the résumé and contact pages.
- `.gitignore`: Specifies files and directories to be ignored by Git.

## How to Run the Project
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/Simple-Resume-Project.git
    ```
2. Open `index.html` in a web browser to view the résumé.
3. Open `contact.html` in a web browser to view the contact form and map.

## References
- [HTML5 Documentation by MDN](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
- [CSS Documentation by MDN](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [Leaflet.js - An Open-Source JavaScript Library for Mobile-Friendly Interactive Maps](https://leafletjs.com/)
- [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
- [W3Schools CSS Tutorial](https://www.w3schools.com/css/)

## Notes
- Remember to replace the placeholder content with actual content for the fictitious person.
- Ensure you have an active internet connection to load the map tiles from OpenStreetMap.
- Modify the coordinates in `contact.html` to change the location displayed on the map.

### HTML (contact.html)

- `<!DOCTYPE html>`: Declares the document type and version.
- `<html lang="en">`: Sets the language for the document.
- `<head>`: Contains meta-information about the document (character set, viewport settings, title, and link to CSS).
- `<link rel="stylesheet" href="styles.css">`: Links to the external CSS file.
- `<link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css" />`: Links to the Leaflet CSS file for map styling.
- `<body>`: Contains the content of the document.
- `<header>`, `<section>`, `<footer>`: Define different sections of the document.
- `<form>`: Contains form elements for user input.
- `<div id="map">`: Placeholder for the map.
- `<script>`: Contains JavaScript to initialize and display the map.
- Leaflet.js library is included for map functionality.

### CSS (styles.css)

- `body`: Sets the font family, margin, padding, background color, and text color for the entire document.
- `header`: Styles the header section with a background color, text color, padding, and text alignment.
- `header h1`: Removes the default margin for the header title.
- `section`: Styles each section with padding, margin, background color, border radius, maximum width, and a box shadow.
- `footer`: Styles the footer with text alignment, padding, background color, text color, fixed position at the bottom, and full width.
- `ul`: Removes the default list style and padding for unordered lists.
- `ul li`: Adds margin to each list item.
- `form label`: Styles form labels to be displayed as block elements with margin.
- `form input, form textarea`: Styles form inputs and textarea with width, padding, margin, border, and border radius.
- `form button`: Styles the form submit button with padding, background color, text color, border, border radius, and cursor style.
- `form button:hover`: Adds a hover effect to the form submit button.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

