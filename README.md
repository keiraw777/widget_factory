# My Widget Store

This is a simple responsive e-commerce website built with HTML, CSS, JavaScript, and MDUI.

## Features

* Browse and select products
* Choose product quantities and colors
* Enter a shipping address
* Select a shipping speed
* View an order summary and total cost
* Light/dark theme support
* Responsive layout for desktop, tablet, and mobile
* Uses browser storage to keep order information between pages

## Technologies

* HTML5
* CSS3
* JavaScript
* MDUI
* Google Material Icons
* Google Fonts

## Project Structure

```text
.
├── index.html
├── shipping.html
├── summary.html
├── style.css
├── light.css
├── script.js
├── widgets_data.js
├── favicon.ico
└── images/
    ├── toyboat.jpg
    ├── paperplane.jpg
    ├── stuffedanimal.jpg
    └── traincar.jpg
```

## Running the Project

1. Download or clone the project.
2. Make sure all files and the `images` folder are in the correct locations.
3. Open `index.html` in a web browser.

Note: for best results, you can also run the project with a simple local development server such as VS Code Live Server.

## Pages

* `index.html` contains product selection and checkout
* `shipping.html` contains shipping address and delivery method
* `summary.html` contains the final order summary

## Notes

Order and theme information are stored locally in the browser, so no backend or database is required.