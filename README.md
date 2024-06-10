# Freshcery

## Overview

**Freshcery** is a sophisticated grocery shopping platform developed using PHP, MySQL, CSS, and HTML. This application aims to provide users with an exceptional online shopping experience, incorporating animated CSS elements, a captivating landing page with embedded video content, and a comprehensive set of features including user authentication, a robust cart system, and multiple checkout and address options.

## Features

- **Animated CSS Content**: Engaging animations to enhance user interaction.
- **Landing Page with Video Embed**: An attractive and dynamic landing page featuring embedded video to captivate user interest.
- **User Authentication**: Secure login and registration functionalities.
- **Cart System**: Efficient management of user-selected products.
- **Checkout and Address Options**: Flexible and user-friendly checkout process with multiple address management capabilities.
- **Responsive Design**: Optimized for various devices to ensure a seamless experience across all platforms.

## Installation

Follow these steps to set up the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Vedang1102/freshcery.git
   cd freshcery
   ```

2. **Configuration**:
   - Rename the `config.sample.php` file to `config.php`.
   - Update the `config.php` file with your database credentials.

3. **Database Setup**:
   - Import the `database.sql` file into your MySQL database to create the necessary tables.
   ```sql
   mysql -u your_username -p your_database_name < database.sql
   ```

4. **Run the Application**:
   - Start your local development server:
     ```bash
     php -S localhost:8000
     ```
   - Open your browser and navigate to `http://localhost:8000`.

## Project Structure

- `index.php`: The main entry point of the application.
- `config.php`: Configuration file for database connections.
- `assets/`: Directory containing CSS, JavaScript, images, and other static files.
- `includes/`: PHP files included in various parts of the application (e.g., header, footer, database connection).
- `pages/`: Contains various pages such as login, register, cart, checkout, etc.
- `freshcery.sql`: SQL file to set up the database schema.

![php1](https://github.com/Vedang1102/freshcery/assets/58174308/9215e9f4-b6e5-4f1a-a5f7-5f73dc900ec7)

![php2](https://github.com/Vedang1102/freshcery/assets/58174308/34205dda-5c3a-49d9-b0f6-1b84876131e3)

![php4](https://github.com/Vedang1102/freshcery/assets/58174308/d15e0785-8ac0-449e-b876-416e3fa52469)

![php5](https://github.com/Vedang1102/freshcery/assets/58174308/4a72c5eb-2d5c-4a04-8bcc-4a07ddd1342e)


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [PHP](https://www.php.net/)
- [MySQL](https://www.mysql.com/)
- [CSS](https://www.w3.org/Style/CSS/Overview.en.html)
- [HTML](https://html.spec.whatwg.org/)
