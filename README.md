# Date Formatter

## Description

The **Date Formatter** project is a web-based application that demonstrates how to use the JavaScript `Date` object to format and display the current date in various formats. The user can select their preferred date format from a dropdown menu, and the application dynamically updates the displayed date accordingly.

## Features

- Displays the current date in the format `Day-Month-Year` by default.
- Provides multiple date format options for users to choose from:
  - `Day-Month-Year`
  - `Year-Month-Day`
  - `Month-Day-Year Hours:Minutes`
- Dynamically updates the date format based on user selection.
- Responsive and styled user interface.

## Project Structure

- `index.html` - The main HTML file containing the structure of the web page.
- `styles.css` - The CSS file responsible for styling the page.
- `script.js` - The JavaScript file handling the logic for date formatting and user interaction.

## Installation

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in your browser to view and interact with the application.

## Usage

1. Open the application in a browser.
2. View the current date displayed in the default format: `Day-Month-Year`.
3. Use the dropdown menu to select a different date format:
   - `Year-Month-Day`: Displays the date in reverse order.
   - `Month-Day-Year Hours:Minutes`: Displays the date with time details.
4. The displayed date will update in real-time based on your selection.

## Code Explanation

### JavaScript (`script.js`)

- Retrieves the current date using the `Date` object.
- Dynamically formats the date based on the selected option in the dropdown menu.
- Listens for changes in the dropdown and updates the displayed date format accordingly.

## Example

- **Default Format**: `1-12-2024`
- **Selected Format**: 
  - `Year-Month-Day`: `2024-12-01`
  - `Month-Day-Year Hours:Minutes`: `12-01-2024 14 Hours 30 Minutes`

## Demo

1. Open the `index.html` file in any modern web browser.
2. Interact with the dropdown to see the date format change in real-time.