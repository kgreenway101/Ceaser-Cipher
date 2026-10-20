# Caesar Cipher

## Overview
This project is a simple web-based Caesar Cipher encryption tool built using HTML, CSS and JavaScript. It allows users to enter a message and encrypt it by shifting each letter a specified number of places through the alphabet.


## Features
- **Message input:** Enter a message to encrypt.
- **Shift value:** Choose the number of positions each letter moves through the alphabet.
- **Live encryption:** The encrypted message updates as you type.
- **Alphabet wrapping:** Letters wrap around to the beginning of the alphabet when the shift passes `z`.
- **Input filtering:** The current implementation converts uppercase letters to lowercase and removes unsupported characters.
- **Responsive styling:** The page uses CSS to adapt its background and layout to different screen sizes.

## Technologies Used
- **HTML5** – Structures the webpage and input fields.
- **CSS3** – Styles the interface, typography, colours and background image.
- **JavaScript** – Handles user input and performs the encryption algorithm.

## How It Works
The Caesar Cipher is a substitution cipher that shifts each letter in a message by a fixed number of positions in the alphabet.

For example, with a shift value of `2`:

input = "abcdefg"
encrypted output = "cdefghi"

The JavaScript converts each letter into its character code, adds the shift value, and wraps the result around the alphabet when necessary.

## How to Run
1. Clone or download this repository.
2. Ensure `Ceaser_HTML.htm` and `background.jpg` are in the project folder.
3. Open the project in Visual Studio Code.
4. Open `Ceaser_HTML.htm` in a web browser, or use the Live Server extension.
5. Enter a message and a shift value to see the encrypted output.

## Project Structure
```text
Ceaser-Cipher/
├── Ceaser_HTML.htm
├── background.jpg
├── README.md
└── .gitignore
```

## Limitations
- The cipher currently supports lowercase English letters only.
- Unsupported characters are removed rather than preserved.
- This is an educational project and is not suitable for securing sensitive information. Caesar Cipher encryption is easy to break.

## Future Improvements
- Preserve spaces and punctuation in messages.
- Validate shift values and support negative shifts.
- Add a decryption feature.
- Improve accessibility and mobile responsiveness.
- Separate the HTML, CSS and JavaScript into individual files.

## Author
Created as a web development project to explore HTML, CSS, JavaScript, user input handling and basic encryption algorithms.
