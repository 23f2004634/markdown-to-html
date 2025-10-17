# Markdown to HTML Converter

A simple, single-page web application that converts a Markdown file (`input.md`) into HTML and renders it directly in the browser. It leverages the `marked` library for efficient client-side Markdown parsing and Tailwind CSS for a responsive, modern design.

## Features

-   **Client-side Conversion**: Markdown content from `input.md` is parsed and converted to HTML entirely within the user's browser.
-   **Responsive Design**: Built with Tailwind CSS, ensuring a clean and adaptable layout across various devices and screen sizes.
-   **Single-File Deployment**: The entire application is contained within a single `index.html` file, making it incredibly easy to deploy and share.
-   **No Backend Required**: Runs purely on the client-side, eliminating the need for server-side processing.

## Project Structure

-   `index.html`: The main application page containing all the HTML, CSS (via Tailwind CDN), and JavaScript (for `marked.js` CDN and conversion logic).
-   `input.md`: The Markdown file whose content will be read and rendered as HTML. **Ensure this file is in the same directory as `index.html`**.
-   `README.md`: This README file, providing an overview and instructions.
-   `LICENSE`: The MIT License for this project.

## Usage

To use this application, follow these simple steps:

1.  **Place `input.md`**: Ensure that your Markdown content is saved in a file named `input.md` in the same directory where `index.html` resides.
2.  **Open `index.html`**: Simply open the `index.html` file in your preferred web browser.

The browser will automatically fetch the `input.md` file, convert its content to HTML, and display it on the page.

## Technologies Used

-   **HTML5**: For the foundational structure of the web page.
-   **Tailwind CSS (CDN)**: For utility-first CSS styling and responsive design.
-   **Marked.js (CDN)**: A high-performance Markdown parser and compiler for the web, used for converting Markdown to HTML.

## License

This project is licensed under the MIT License. See the `LICENSE` file for full details.