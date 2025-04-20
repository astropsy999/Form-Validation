# Simple Form Validation UI

A frontend project demonstrating client-side form validation using HTML, CSS, and vanilla JavaScript.

## Features

* A standard user registration form (Username, Email, Password, Confirm Password).
* Client-side validation triggered on form submission.
* Validation checks include:
  * Required fields
  * Username length (min/max)
  * Password length (min/max)
  * Valid email format (using regex)
  * Password confirmation match
* Visual feedback for valid/invalid fields using CSS classes (`.success`, `.error`).
* Displays specific error messages below invalid fields.

## Technologies Used

* HTML
* CSS
* JavaScript (Vanilla)

## Key Concepts Demonstrated

* HTML Form Structure
* CSS Styling for Forms (including validation states)
* DOM Manipulation (selecting elements, reading values, modifying classes and text)
* Event Handling (listening for form `submit` event)
* Preventing Default Browser Actions (`event.preventDefault()`)
* Writing Reusable JavaScript Functions for Validation Logic
* Basic Regular Expressions for Email Validation

## How to Run

1. Ensure you have the `index.html`, `style.css`, and `script.js` files in the same directory.
2. Open the `index.html` file directly in your web browser.
3. Fill out the form and click "Submit" to see the validation in action.
