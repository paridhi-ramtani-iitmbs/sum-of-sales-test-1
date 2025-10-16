# Overview
This is a single-page web application that fetches sales data from a CSV file, sums up the sales values, and displays the total on the page. The application uses Bootstrap 5 for styling and is fully self-contained.

# Setup
To set up the project, ensure you have the following:
- A web server to serve the `index.html` file.
- The `data.csv` file in the same directory as the `index.html`.

# Usage
1. Place the `index.html` and `data.csv` files in the same directory.
2. Run a local web server (e.g., using Python's `http.server`).
3. Open your web browser and navigate to `http://localhost:<port>/index.html` to view the application.

The total sales from the CSV data will be displayed on the page. The title will include a randomly generated seed.

# Improvements
In this version, a Bootstrap table has been added to display each product alongside its total sales. The total sales calculation has been enhanced to ensure accuracy after rendering the product list. The table structure allows for better organization and presentation of sales data.