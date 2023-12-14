# Compound Interest Calculator

## Overview

This is a React application that provides a Direct Deposit Enrollment form and a Compound Interest Calculator. Users can fill out the deposit enrollment form with their account details, and the app calculates the compound interest based on the entered information.

## Installation

To run the application locally, follow these steps:

1. Clone the repository: `git clone `
2. Navigate to the project directory: `cd interest-calculator-app`
3. Install dependencies: `npm install`
4. Start the development server: `npm start`
5. Open your browser and visit `http://localhost:3000` to view the app.

## Usage

### Direct Deposit Enrollment Form

1. Access the form by navigating to the home page.
2. Fill out the required information, including account number, routing number, amount, and frequency.
3. Click the "Submit" button to proceed.
4. You will be redirected to the Interest Calculator page with the form values passed as state.

### Compound Interest Calculator

1. Access the Interest Calculator page.
2. Select a date using the date picker.
3. Click the "Calculate" button to see the compound interest based on the entered deposit details.
4. The result will be displayed below the button.

## Components

### App

The main component that sets up the React Router and includes the layout for the entire application.

### DepositEnrollmentForm

This component renders the Direct Deposit Enrollment form. It utilizes Formik for form management and validation.

### InterestCalculator

This component handles the Compound Interest Calculator. It uses the MUI date picker for date selection and calculates interest based on the provided deposit details.

## Dependencies

- React
- React Router
- Material-UI
- Formik
- MUI X Date Pickers
- Dayjs

## License

This project is licensed under the [MIT License](LICENSE).