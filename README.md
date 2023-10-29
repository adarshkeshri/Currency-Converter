# Currency Converter using Python

Welcome to the Currency Converter project! This is a simple Python program that allows you to convert currency values in real-time using exchange rate data from the [exchangerate-api.com](https://exchangerate-api.com/) API. This README file provides information about the project and how to use it.

## How it Works

The project consists of two Python files:

1. `Main.py`: This file contains the graphical user interface (GUI) for the currency converter. It uses the Tkinter library to create a simple interface where you can select the source currency, target currency, and enter an amount to convert. It then displays the converted amount in real-time.

2. `Converter.py`: This file defines a `RealTimeCurrencyConverter` class, which is responsible for fetching exchange rate data from the API and performing currency conversions. The class has a `convert` method that takes the source currency, target currency, and amount as input and returns the converted amount.

## How to Use

To use the Currency Converter, follow these steps:

1. Clone or download this GitHub repository to your local machine.

2. Ensure you have Python installed on your system. If not, you can download it from [python.org](https://www.python.org/downloads/).

3. Open a terminal or command prompt and navigate to the project's directory.

4. Run the `Main.py` file by executing the following command:

   ```
   python Main.py
   ```

   This will open the Currency Converter GUI.

5. Use the following steps within the GUI:

   - Select the source currency from the left dropdown.
   - Enter the amount you want to convert in the text field.
   - Select the target currency from the right dropdown.
   - Click the "Convert" button.

   The converted amount will be displayed in the white box on the right.

6. You can close the GUI when you're done.

## Dependencies

The project relies on the following Python libraries:

- Tkinter: Used for creating the graphical user interface.
- Requests: Used to make HTTP requests to fetch exchange rate data from the API.

You can install the necessary dependencies using pip:

```
pip install requests
```

## Note

- This project uses exchange rate data from the [exchangerate-api.com](https://exchangerate-api.com/) API. Make sure you have an internet connection while using this application.

- The exchange rates are based on the data provided by the API, and actual exchange rates may vary.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository, make your changes, and create a pull request. We welcome any improvements or additional features to make this Currency Converter even better!

Thank you for using the Currency Converter, and we hope it serves you well! If you have any questions or encounter issues, please don't hesitate to contact the project contributors.
