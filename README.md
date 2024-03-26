# Review & Rating System in PHP & MySQL using Ajax

This PHP and JavaScript code implements a review and rating system where users can submit reviews and ratings for a product. It also displays the average rating, total reviews, and distribution of ratings (e.g., five-star, four-star, etc.).

## Features

- **Submit Review**: Users can write reviews and submit ratings for a product.
- **Display Average Rating**: The system calculates and displays the average rating based on all submitted reviews.
- **Display Total Reviews**: Shows the total number of reviews submitted for the product.
- **Display Rating Distribution**: Displays the distribution of ratings, including the number of five-star, four-star, three-star, two-star, and one-star reviews.
- **AJAX Interaction**: Utilizes AJAX for asynchronous interaction with the server to submit reviews and update review data without page reload.

## Files Included

- **Rating.php**: PHP script handling the submission and retrieval of review data from the database.
- **index.html**: HTML file containing the user interface for the review and rating system.
- **Bootstrap CSS**: External CSS file for styling the HTML elements.
- **Font Awesome CSS**: External CSS file for displaying icons.
- **jQuery Library**: External JavaScript library for DOM manipulation and AJAX requests.

## Usage

1. **Setup Database**: Create a MySQL database named `database` and import the necessary tables.
2. **Update Database Connection**: Update the database connection details in the `Rating.php` script (`$connect` variable).
4. **Load Files**: Host the PHP and HTML files on a server with PHP support.
5. **Access**: Open the `index.html` file in a web browser to access the review and rating system.

## Notes

- Ensure that the PHP environment supports PDO for MySQL database interaction.
- Make sure to sanitize user inputs to prevent SQL injection and XSS attacks.
- Review the PHP and JavaScript code comments for better understanding of the implementation details.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
