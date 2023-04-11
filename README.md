<!-- @format -->

# Chasing the Clicks 
## https://ubakaliya.github.io/Chasing-the-Clicks/

-   Chasing the Clicks is a simple web application that allows users to click a button to increment a counter. The counter is stored in the user's browser using localStorage, so the counter persists even when the user refreshes the page. In addition to the counter, the application also displays a table that shows the distribution of clicks by geography.

## How it works

-   The application is built using HTML, CSS, and JavaScript. The HTML file contains a button element and a div element that displays the current click count. The JavaScript code uses the localStorage API to store and retrieve the click count, and adds a click event listener to the button to increment the count when the button is clicked.

-   To display the distribution of clicks by geography, the application uses a simple API to determine the user's country based on their IP address. When the user clicks the button, the application sends a request to the API to get the user's country, and then adds a new row to the table with the country name and the current click count.

## How to use it

To use the application, simply open the ```https://ubakaliya.github.io/Chasing-the-Clicks/``` file in a web browser. Click the "Click me!" button to increment the counter, and the table will update to show the distribution of clicks by geography.



## License

Chasing the Clicks is licensed under the Uvaish License.

## Credits

Chasing the Clicks was created by Uvaish Bakaliya.
