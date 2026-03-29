# Age and Student Status Checker

A simple, interactive JavaScript application that interacts with the user via standard browser dialog boxes (`prompt`, `confirm`, `alert`). The program collects the user's age, validates the input, and asks about their student status to display a customized welcome message.

## Features

- **Input Collection:** Uses `prompt()` to ask for the user's age.
- **Type Conversion & Validation:** Converts the input to a number using `Number()` and validates against `NaN` to ensure proper numeric input.
- **Interactive Flags:** Uses `confirm()` to check if the user is currently a student.
- **Conditional Logic:** Evaluates age restrictions (<18) and student status to output the correct response.

## How It Works

1. Upon opening the page, a prompt appears asking for your age.
2. If the input is empty or not a number, an alert warns: *"Geçerli bir yaş giriniz!" (Please enter a valid age!)*.
3. If a valid age is entered, the user is asked if they are a student via a confirm dialog.
4. Based on the responses, one of the following alerts is shown:
   - If age < 18: *"Reşit değilsiniz." (You are underage.)*
   - If age >= 18 and is a student: *"Hoşgeldiniz öğrenci!" (Welcome, student!)*
   - If age >= 18 and not a student: *"Hoşgeldiniz!" (Welcome!)*

## Usage

Simply open the `index.html` file in any modern web browser to run the script. No server, environment setup, or additional dependencies are required.

## Technologies Used

- HTML5
- Vanilla JavaScript
