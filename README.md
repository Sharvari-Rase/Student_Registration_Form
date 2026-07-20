# Student_Registration_Form

A simple student registration web app built with HTML, CSS, and JavaScript. Fill in your details, and the form validates everything before showing a success message with your information.

## Features

- Collects Full Name, Email, Mobile Number, Password, Confirm Password, Gender, and City
- Validates every field before submitting:
  - No field can be empty
  - Full Name must contain only letters and spaces
  - Email must be in a valid format
  - Mobile Number must be exactly 10 digits
  - Password must be at least 8 characters
  - Confirm Password must match Password
  - Gender and City must be selected
- Shows a clear error message under any field that fails
- On success, shows "Student Registration Successful!" with a details table
- Fully responsive design

## Files

```
registration-form/
├── index.html   -> Page structure
├── style.css    -> Styling
└── script.js    -> App logic
```

## How to Run

1. Download all three files into the same folder.
2. Open `index.html` in any web browser.
3. Fill in the form and click "Register"!

No installation or setup needed — it's plain HTML, CSS, and JavaScript.

## How to Use

- **Register**: Checks every field. If something's wrong, an error message appears below that field. If everything's correct, a success card appears with your details in a table.
- **Reset**: Clears the form so you can start over.
- **Register Another Student**: Appears after a successful registration — takes you back to a blank form.

## Built With

- HTML5
- CSS3
- Vanilla JavaScript (no frameworks or libraries)
