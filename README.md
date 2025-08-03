# IMDb Data Extraction – UiPath Project

## Overview
This UiPath project automates the extraction of movie or TV show data from the IMDb website. It retrieves information such as title, rating, release year, and genre, and exports it into an Excel file for further analysis or reporting.

## Features
- Extracts movie/show title, rating, year, and genre
- Handles pagination to cover multiple pages of search results
- Uses dynamic selectors to adapt to web changes
- Exports structured data to Excel
- Includes basic error handling

## Technologies Used
- UiPath Studio
- Excel Activities
- Data Scraping Wizard
- Dynamic Selectors
- Try-Catch for error handling

## How to Use
1. Open the project in UiPath Studio.
2. Enter the IMDb URL or search keyword in the config (if applicable).
3. Run the automation.
4. Extracted data will be saved in the `Output` folder as an Excel file.

## Prerequisites
- UiPath Studio installed
- Internet connection
- Excel installed (for opening the output file)

## Output
The automation generates an Excel file with columns:
- Title
- Rating
- Release Year
- Genre

## Author
This project was created as part of an RPA learning path to practice web data scraping using UiPath.

---

Feel free to customize the config and add more fields as needed.
