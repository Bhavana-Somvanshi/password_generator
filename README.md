Random Password Generator README

This repository contains a simple web-based random password generator. It generates secure passwords based on user-defined criteria such as length, character types (uppercase, lowercase, numbers, symbols), and allows you to copy the generated password to your clipboard.
Table of Contents

    Demo
    Features
    Usage
    How it Works
    Customization
    Contributing
    License

Demo

You can see a live demo of the Random Password Generator here, where you can try out the password generation functionality.
Features

    Generate random passwords with various options:
        Password length selection.
        Inclusion of uppercase characters (A-Z).
        Inclusion of lowercase characters (a-z).
        Inclusion of numbers (0-9).
        Inclusion of symbols (~!@#$%^&*()_+/).
    Visual representation of the generated password.
    Generate passwords of your desired length.
    Easy-to-use web interface.

Usage

    Clone or download this repository to your local machine.
    Open the index.html file in a web browser to access the password generator.
    Select your preferred options:
        Set the password length using the input field (min: 2, max: 30, default: 10).
        Check/uncheck the character type options (uppercase, lowercase, numbers, symbols) as per your requirements.
    Click the "Generate" button to generate a random password.
    The generated password will be displayed in the "Testing" box.
    You can copy the password to your clipboard by selecting it and using the copy functionality of your browser.

How it Works

The password generation is performed using JavaScript. The code consists of the following key components:

    An array of character sets for uppercase, lowercase, numbers, and symbols.
    A getRandomData function to pick a random character from a given character set.
    The generatePassword function that uses the selected options to generate a password and ensures the password meets the specified length.
    An event listener for the "Generate" button to trigger the password generation.
    A truncateString function to limit the password to the specified length.
    HTML and CSS code for the user interface.

Customization

You can customize the password generator further by modifying the following aspects:

    Character sets: You can adjust the character sets by changing the values in the upperSet, lowerSet, numberSet, and symbolSet variables in the JavaScript code.
    Styling: You can modify the CSS in the style.css file to change the appearance of the user interface.

Contributing

If you would like to contribute to this project, feel free to submit issues or pull requests on the GitHub repository.
License

This project is licensed under the MIT License.

Enjoy generating secure random passwords with this simple web-based tool!
