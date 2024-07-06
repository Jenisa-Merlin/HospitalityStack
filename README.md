# HospitalityStack

## Overview
The Hotel Management System is a web-based application developed using PHP, JavaScript, Bootstrap, and CSS. It includes separate admin and user interfaces. The admin side handles booking management, profit tracking, room operations (addition and deletion), and more. Meanwhile, the user section allows browsing of pages like homepage, about, services, rooms, and contact us, with the ability to make room bookings directly from the website.

## Features
- **Admin Section:** Manages bookings, profit calculations, room operations, and other administrative tasks.
- **User Section:** Allows users to browse information pages and book rooms as per their requirements.

### Installation Instructions
To run the project locally:
1. Ensure you have a virtual server installed, such as XAMPP (for Windows).
2. Download and extract the project files.
3. Copy the extracted folder into `xampp/htdocs/`.
4. Open your web browser and navigate to `http://localhost/phpmyadmin/`.
5. Create a new database named `hotel`.
6. Select the `hotel` database, navigate to the "Import" tab, choose the `hotel.sql` file located in the project's `Hotel` folder, and import it.
7. Once the database is imported successfully, access the application by visiting `http://localhost/Hotel/` in your web browser.
8. To access the admin panel, go to `http://localhost/Hotel/admin/index.php`.

### Note
- Ensure you have Apache and MySQL services running in your XAMPP control panel before proceeding with installation.
