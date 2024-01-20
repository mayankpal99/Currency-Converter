# Currency Converter

This repository contains a simple currency converter web application built using HTML, CSS, and JavaScript. The converter allows users to input an amount in a specified currency, select the source and target currencies, and obtain the converted amount based on the latest exchange rate.

## Table of Contents
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Styling](#styling)
- [Scripts](#scripts)
- [API Integration](#api-integration)

## Project Structure
The project consists of the following files:

1. **index.html**: The main HTML file that defines the structure of the web page, including the form for currency conversion.
2. **styles.css**: The CSS file containing styles for the web page layout and elements.
3. **codes.js**: A JavaScript file that includes the currency codes and their corresponding country codes.
4. **script.js**: The main JavaScript file handling user interactions and API calls.

## Usage
To use the currency converter:
1. Open the `index.html` file in a web browser.
2. Enter the amount you want to convert in the "Enter Amount" input field.
3. Select the source currency from the "From" dropdown.
4. Select the target currency from the "To" dropdown.
5. Click the "Get Exchange Rate" button to obtain the converted amount.

## Styling
The styling is kept minimalistic and user-friendly. The background color of the page is set to a light blue (#40A2D8), and the container holding the converter form has a light blue background (#E9F6FF). Input fields, buttons, and dropdowns have consistent styling for a cohesive user interface.

## Scripts
The JavaScript files (`codes.js` and `script.js`) handle the dynamic population of currency dropdowns, flag updates, and the currency conversion logic. Event listeners are used to trigger actions when users interact with the form elements.

## API Integration
The converter fetches the latest exchange rate data from the [Currency API](https://github.com/fawazahmed0/currency-api) using the `fetch` API. The exchange rates are based on the user-selected source and target currencies, and the converted amount is displayed on the page.

Feel free to explore and modify the code to suit your needs or contribute to its improvement. If you have any questions or suggestions, please create an issue or submit a pull request.
