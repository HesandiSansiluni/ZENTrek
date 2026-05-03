# ZENTrek
ZENTrek is a travel-focused 'Tour Guide Booking System' web application designed to help users discover and explore destinations across Sri Lanka. The platform allows travelers to identify popular and hidden locations, learn detailed information about each place, and connect with local guides for a better travel experience.

# Summary
Browse guide profiles and bios
Check guide availability and make bookings
Manage bookings (view/cancel)
Basic payment workflow structure
Reviews and feedback stored in MySQL

# Tech stack
Frontend: HTML5, CSS3, JavaScript
Backend: PHP (PDO recommended)
Database: MySQL / MariaDB

# Requirements
PHP 7.4 or newer with PDO extension
MySQL or MariaDB
XAMPP or similar Apache + PHP environment

# Quick start
Install and run XAMPP (start Apache and MySQL).
Copy the project into your web root, for example:
Copy-Item -Path . -Destination 'C:\xampp\htdocs\zentrek' -Recurse
Create a database (e.g., zentrek) and import the schema:
mysql -u root -p zentrek < database/zentrek.sql
Copy config.example.php to config.php and update DB credentials.
Open the site at: http://localhost/zentrek/

# Configuration
Use config.example.php as the template. The example includes PDO connection usage and recommended settings. Do not commit config.php with sensitive credentials.

# Contributing
Contributions are welcome. Open an issue to discuss changes, then submit a pull request from a feature branch.

# License
This project is licensed under the MIT License — see LICENSE.

# Contact
https://github.com/HesandiSansiluni

License
This project is licensed under the MIT License — see LICENSE.
