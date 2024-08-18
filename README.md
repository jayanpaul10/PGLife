# PGLife

PGLife is a web application built using PHP and MySQL that provides a platform for students and working professionals to find paying guest (PG) accommodations. The application is currently running on localhost and is available on GitHub.

## Features

- **User Authentication**: Users can register and log in to their accounts.
- **PG Listings**: View a variety of PG accommodations filtered by city, amenities, and price range.
- **Search Functionality**: Users can search for PGs based on their preferences.
- **Detailed PG Pages**: Each listing has a detailed page with information about the accommodation, including images, price, and amenities.
- **Booking and Contact Information**: Users can view booking details and contact information of the PG owners.
- **Admin Panel**: Manage PG listings, user accounts, and more through the admin panel.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Server**: Apache (XAMPP or WAMP recommended for local development)

## Installation and Setup

### Prerequisites

- XAMPP/WAMP or any local server setup
- PHP 7.4 or higher
- MySQL

### Steps to Run on Localhost

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/jayanpaul10/PGLife.git
   ```

2. Move to the Project Directory:     
    ```bash
    cd PGLife
    ```

Start the Local Server:

- Open XAMPP/WAMP and start the Apache and MySQL modules.

3. Import the Database:

- Open PHPMyAdmin (http://localhost/phpmyadmin).
- Create a new database named pg_life.
- Import the pg_life.sql file located in the database folder of the project.

4. Configure Database Connection:

 - Open the config.php file in the config folder.

5. Update the database credentials:
```
$dbHost = 'localhost';
$dbUsername = 'root';
$dbPassword = '';
$dbName = 'pg_life';
```
Access the Application:
Open your browser and navigate to http://localhost/PGLife.
