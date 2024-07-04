## Flask Application Design

### HTML Files
- `index.html`:
    - This will be the landing page for the application with form for user to input URL of product's front facing photo.
    - It may also contain instructions on how to use the application.
- `results.html`:
    - This page will display the generated background image for the product.

### Routes
- `/`:
    - This route will render the `index.html` file, which includes the form for the users to input the imageUrl  of product.
- `/generate`:
    - This route will receive the form data from the index page and use it to generate a background image for the product.
    - It will then render the `results.html` file, displaying the generated image.