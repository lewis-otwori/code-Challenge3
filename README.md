# code-Challenge3

Movie Ticket Booking System
This is a simple web application that allows users to view movie details and book tickets for shows.

Core Deliverables
As a user, you can:

View the details of the first movie, including its poster, title, runtime, showtime, and available tickets when the page loads. The number of available tickets will be derived by subtracting the number of tickets_sold from the theater's capacity.

View a menu of all movies on the left side of the page in the ul#films element when the page loads.

Buy a ticket for a movie. After clicking the "Buy Ticket" button, you will see the number of available tickets decreasing on the frontend. You will not be able to buy a ticket if the showing is sold out (if there are 0 tickets available).

Endpoints
This application has the following endpoints:

GET /films: Returns a list of all movies, including their details.
GET /films/1: Returns details of the first movie.

Technologies Used
This project was built using the following technologies:

Node.js
HTML
CSS
JavaScript
Contributing
If you want to contribute to this project, you can fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT License.
