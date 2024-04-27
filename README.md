# Currency Converter App Documentation

### Overview

This Currency Converter App is a simple React application that allows users to convert an amount from one currency to another using real-time exchange rates fetched from an API.

### Features

- Convert currency from one type to another.
- Fetch real-time exchange rates from the API.
- Display the converted amount.

### Components

_App Component_ : The main component of the application that handles currency conversion and UI rendering.

### State Variables

- _amount_: Represents the amount to be converted.
- _fromCurrency_: Represents the currency to convert from.
- _toCurrency_: Represents the currency to convert to.
- _converted_: Stores the converted amount.
- _loading_: Indicates whether data is being fetched.

### Dependencies

- _React_: Used for building the UI components.
- _useState_: Used for managing state variables.
- _useEffect_: Used for fetching data and handling side effects.
- _fetch_: Used for making API requests.

### API Integration

The app integrates with the Frankfurter API to fetch real-time exchange rates for currency conversion.

### Development Notes

The conversion logic is triggered whenever there are changes in amount, fromCurrency, or toCurrency using the useEffect hook.
Input fields are disabled while data is being fetched (loading state) to prevent user interactions during this period.
