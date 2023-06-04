# Danny's Record Collection (Client-side Version)

This project is a client-side web application that displays and analyzes Danny's record collection. It provides a user interface to browse through the records, view statistics, and see information about the collection. The client-side version is designed to be easily deployed to the internet without the need for a back-end server.

## Features

- Display of record collection: The web application presents a table that shows the title, artist, release year, and format of each record in Danny's collection. The table is populated dynamically using data from a JSON file.
- Navigation: Users can navigate through the record collection using "Previous" and "Next" buttons. The "Previous" button is disabled when viewing the first record.
- Statistics: The application displays statistics about the record collection. It shows the total number of records and presents a chart that visualizes the distribution of records by year. Additionally, it provides a table with the most frequent artists in the collection, along with the number of records for each artist.

## Deployment

The client-side version of this project is already deployed and accessible on the internet. You can visit the application by navigating to [https://records-client-side.pages.dev](https://records-client-side.pages.dev) in your web browser.

## Project Structure

The client-side version of the project consists of the following files:

- `index.html`: This file contains the HTML structure of the record collection page. It includes various elements such as buttons, tables, and charts.

- `styles.css`: This file contains the CSS styles for the record collection page.

- `scripts.js`: This file contains the JavaScript code that handles the dynamic behavior of the web page, including record navigation, statistics generation, and chart rendering.

- `records.json`: This file contains the record data in JSON format. Modify this file or replace it with your own record data to customize the collection.

## Usage

- Pagination: Click the "Previous" and "Next" buttons to navigate through the records.

- Sorting: Click on the table headers (Title, Artist, Release Year, Format) to sort the records based on the selected column. The sort order is indicated by an arrow (▲ for ascending, ▼ for descending).

- Statistics: The "Total Records" section displays the total number of records in the collection.

- Records By Year: The chart shows the number of records released per year.

- Most Frequent Artists: The table displays the artists with the highest number of records in the collection.