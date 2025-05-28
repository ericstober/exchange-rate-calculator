# Exchange Rate Calculator

A lightweight and intuitive web application for converting currencies using real-time exchange rate data. The project leverages JavaScript, HTML, and CSS for the frontend and integrates with an external API to fetch up-to-date exchange rates.

## Features

- **Real-time Currency Conversion**: Convert between a wide range of currencies with updated exchange rates.
- **Global Currency Support**: Includes popular and lesser-used currencies for versatile use.
- **Responsive Design**: Adapts to all screen sizes, from desktops to mobile devices.
- **Clean Interface**: User-friendly and aesthetically pleasing design for a seamless experience.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/ericstober/exchange-rate-calculator.git
```

2. Navigate to the project directory:

```bash
cd exchange-rate-calculator
```

3. Open the `index.html` file in your browser

## API Integration

This project fetches exchange rate data from [ExchangeRate-API](https://www.exchangerate-api.com/). Replace the API URL in the code with your own.

```js
fetch(`https://apiurlhere/${currency_one}`);
```

## Acknowledgments

- API Provider: [ExchangeRate-API](https://www.exchangerate-api.com/)
