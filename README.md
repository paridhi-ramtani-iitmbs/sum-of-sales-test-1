# Overview
This web application is a single-page site that fetches sales data from a CSV file, sums the sales column, and displays the total sales amount. It utilizes Bootstrap 5 for styling and provides a responsive design.

# Setup
1. Ensure you have a server environment to serve the HTML file and the `data.csv` file.
2. Place the `data.csv` file in the same directory as the `index.html` file.

# Usage
1. Open the `index.html` file in a web browser.
2. The application will fetch the sales data from `data.csv`, calculate the total sales, and display it on the page with a header.

# Improvements
- This version includes dynamic title generation based on a random seed.
- The app now fetches the CSV data using the Fetch API, ensuring it processes the data correctly.
- Bootstrap 5 is loaded from jsdelivr for better styling and responsiveness.