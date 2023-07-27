# Dad-joke-generator
 This repository contains a simple Dad Joke Generator web application built using HTML, CSS, and JavaScript. The application fetches a random dad joke from the "api.api-ninjas.com" API and displays it on the web page when the user clicks the "Tell me a joke" button.

#Features:

Click the "Tell me a joke" button to fetch and display a random dad joke from the API.
The user interface has a clean and minimalist design.
The button is disabled while fetching a joke to prevent multiple requests.
If there is an error during the API request, the application gracefully handles it and displays an appropriate error message.

#How it works:
The application makes an HTTP GET request to the "api.api-ninjas.com" API endpoint to fetch a random dad joke.
The API requires an "X-Api-Key" header with the API key to authenticate the request.
While the joke is being fetched, the "Tell me a joke" button is disabled and displays "Loading..." to indicate ongoing activity.
Once the joke is retrieved, the button is enabled again, and the fetched dad joke is displayed on the webpage.

#Instructions:

Clone this repository to your local machine or download the ZIP file.
Open the "index.html" file in your web browser to run the Dad Joke Generator web application.
Click the "Tell me a joke" button to get a random dad joke and have a good laugh!
Feel free to contribute to this repository by adding more features, improving the UI, or enhancing the error handling. Enjoy the dad jokes and spread some smiles! 😄
