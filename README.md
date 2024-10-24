# Login-page_1
A simple login-page using html &amp; Css!!
# Login-page_1
A simple login-page using html &amp; Css!!
LOGIN PAGE
Overview
This project consists of a simple login page built using HTML and CSS. The page includes a login form with fields for a username and password, and a submit button. The form is styled to have a background image, with elements like the form, input fields, and button styled for better user experience.
Structure
HTML Code
DOCTYPE Declaration:
The <!DOCTYPE html> declaration defines that the document is an HTML5 document.

Head Section:
The <head> section contains metadata, such as the page title (LOGIN PAGE), and links to the styles embedded in the <style> tag.

Body Section:

Contains the actual content of the webpage.
The main component here is a div with the class login, which contains the login form.
The form has:
A heading (<h1>LOG-IN).
Two labeled input fields: one for the username and one for the password.
A submit button for the user to log in.
CSS Styling
Body Styling:
The body is set up to occupy the full height of the viewport (height: 100vh). Flexbox is used to center the login form both horizontally and vertically.

Login Form Styling:
The .login class defines the appearance of the login form container:

It has a fixed width and height (400px by 500px).
A background image is applied with background-size: cover and background-position: center to ensure that the image fits nicely within the form.
A border, box-shadow, and border-radius are added for aesthetic purposes.
Form Layout:
The form itself uses flexbox for layout, allowing for vertical alignment of form elements with consistent spacing using gap: 5px.

Typography:
The heading (h1) and labels have custom styling. The heading has a text-shadow for visual effect, and the font size is set to 40px for emphasis.

Input Fields:
The input fields have rounded corners, padding for comfortable typing, and a semi-transparent background (rgba(255, 255, 255, 0.178)).

Button Styling:
The button is styled with rounded corners (border-radius: 40px), a shadow effect, and a color transition when hovered (background-color: aqua). The button is interactive, with changes in color and shadow when hovered.

Usage
This is a simple, static HTML page for a login form. The form doesn't have any functionality by default to submit the data, as no back-end logic is included. To add functionality, you would need to integrate it with a back-end service for authentication.
