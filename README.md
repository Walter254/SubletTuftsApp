
# Tufts Sublet

## Overview

Tufts Sublet is a web application designed to help students at Tufts University find and list sublet opportunities. The platform allows users to browse available rooms, view detailed descriptions, and contact landlords directly. It aims to simplify the process of finding temporary housing for students.

## Features

- **User-Friendly Interface**: Easy navigation with a responsive design.
- **Room Listings**: Users can view detailed information about available rooms, including images, prices, and descriptions.
- **Contact Landlords**: Directly contact landlords via email for inquiries.
- **Privacy Policy**: A comprehensive privacy policy to inform users about data collection and usage.
- **Room Listing Form**: A form for users to submit their own room listings.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **APIs**: Geoapify for address validation

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Walter254/SubletTuftsApp.git
   cd SubletTuftsApp
   ```

2. Set up the database:
   - Create a MySQL database and import the necessary schema.
   - Update the database connection details in `populate_db.php` and `find_room.php`.

3. Start a local server:
   - You can use XAMPP, MAMP, or any other local server setup to run the PHP files.

4. Access the application:
   - Open your web browser and navigate to `http://localhost/tufts-sublet/index.html`.

## Usage

- **Finding a Room**: Navigate to the "Find Room" section to browse available listings.
- **Listing a Room**: Use the "List Room" section to submit your own room for subletting.
- **Contacting**: Click on the contact button to reach out to landlords directly.

## Privacy Policy

The application includes a privacy policy that outlines how user data is collected, used, and protected. Users are encouraged to read this policy to understand their rights.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

For any questions or feedback, please reach out to us at help@tsublet.com.
