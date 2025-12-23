# Password Strength Indicator

A beginner-friendly JavaScript project that provides real-time feedback on password strength. The input field dynamically shows whether a password is **weak**, **medium**, or **strong** based on its length, with visual cues using color changes.

## Live Demo
Try it live here: [Password Strength Indicator](https://asma-ehsan.github.io/Password-Strength-Indicator/)

## Features
- Real-time password strength feedback as the user types.
- Strength categories based on password length:
  - **Weak:** 1–4 characters
  - **Medium:** 5–8 characters
  - **Strong:** 9+ characters
- Dynamic input border and message color changes.
- Styled placeholder text using the `::placeholder` selector.
- Fully built using HTML, CSS, and vanilla JavaScript.

## How to Use
1. Open `index.html` in your browser.
2. Type your password in the input field.
3. Watch the message below the field update as the password length changes.
4. Colors of the input border and message indicate strength (red = weak, yellow = medium, green = strong).

## What I Learned
- Styling placeholder text separately with `::placeholder`.
- Handling `input` events in JavaScript for real-time interaction.
- Dynamically updating DOM elements (`innerHTML` and `style` properties).
- Using small projects to strengthen understanding of CSS and JavaScript fundamentals.
