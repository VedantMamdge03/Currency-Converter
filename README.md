# Currency Converter

A simple web-based currency converter application that allows users to convert amounts between different currencies.

## Features

- Convert amounts between a wide range of currencies.
- Automatic fetching of the latest exchange rates.
- Display country flags for selected currencies.
- Responsive and user-friendly interface.

## Project Structure

### index.html

The main HTML file which contains the structure of the Currency Converter application.

### script.js

The JavaScript file responsible for the functionality of the currency converter, including fetching exchange rates and updating the UI dynamically.

### codes.js

Contains the countryList object which maps currency codes to their corresponding country codes used for displaying flags.

### style.css

The CSS file to style the application.

## Installation

1. Clone the repository:
    ```sh
    https://github.com/VedantMamdge03/Currency-Converter.git
    ```
2. Navigate to the project directory:
    ```sh
    cd currency-converter
    ```

## Usage

1. Open `index.html` in your favorite web browser.

2. Enter the amount you wish to convert.

3. Select the currencies from the dropdowns for "From" and "To".

4. Click on the "Get Exchange Rate" button to see the conversion result.

## Dependencies

- [Currency API](https://cdn.jsdelivr.net/gh/fawazahmed0/currency-api@1/latest/currencies)
- [Font Awesome](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css)

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.
