# 1. Clear Career (SPA)

This is a Single-Page Application built using vanilla JavaScript, HTML, and CSS. It provides functionality for user authentication, creating, editing, and viewing listings, and navigating between different views within the application.

## Features

- User Authentication: The application supports user authentication with login and registration functionality.
- Listings Management: Users can create new listings, edit existing listings, and view the details of individual listings.
- User Dashboard: The dashboard displays the user's listings and offers.
- Home Page: The home page shows a list of all available listings.
- API Integration: The application communicates with a backend API for data retrieval and modification.

## Getting Started

1. Clone the repository:
   git clone <repository-url>

2. Install dependencies:
   cd <project-directory>
   npm install

3. Configure API Endpoint:
   Update the `api.js` file in the `src` directory with the appropriate API endpoint.

4. Start the application:
   npm start

5. Access the application:
   Open a web browser and visit `http://localhost:3000` to access the application, where `3000` is the port number specified in the console when starting the application.

## File Structure

- `api.js`: Handles API requests and authentication.
- `data.js`: Defines application-specific requests using the API functions.
- `app.js`: Main entry point of the application, sets up routing and handles user authentication and navigation.
- `util.js`: Provides utility functions for managing user data.
- `auth.js`: Defines the view for authentication-related pages (login, registration).
- `create.js`: Defines the view for creating new listings.
- `dashboard.js`: Defines the view for the user dashboard.
- `details.js`: Defines the view for displaying listing details.
- `edit.js`: Defines the view for editing a listing.
- `home.js`: Defines the view for the home page.

## Dependencies

- `lit-html`: A lightweight HTML templating library.
- `page`: A client-side routing library.
