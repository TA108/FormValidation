# Simple Form Validation with jQuery

This is a basic HTML form that performs client-side validation using jQuery.  
It validates user inputs for Email, Phone Number, Password, and Confirm Password fields.

---

## Features

- Checks if the Email field is filled and matches a valid email pattern.
- Checks if the Phone Number field is filled and contains only numbers.
- Checks if the Password and Confirm Password fields are filled and match.
- Displays validation errors dynamically below the form.
- Shows a success message when all inputs are valid.

---

## Files

- `index.html` — The single HTML file containing the form, embedded CSS styling, and jQuery validation script.

---

## How to Use

1. Open `index.html` in any modern web browser.
2. Fill in the form fields and click the submit button.
3. Validation messages will appear if there are errors.
4. A success message will display if all inputs pass validation.

---

## Notes

- The validation runs purely on the client side.
- The submit button uses a jQuery click handler with `e.preventDefault()` to stop actual form submission.
- jQuery is referenced locally in the project as `jquery.js`. Make sure the file exists or update the path accordingly.
- For production use, always implement server-side validation as well.

---

## Dependencies

- [jQuery](https://jquery.com/) (Make sure to have `jquery.js` in the project or update the script source to use CDN.)

---

## License

This project is open-source and free to use.
