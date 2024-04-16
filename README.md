# Smart-Stays
Welcome to our Hotel &amp; PG Booking Platform!  This GitHub repository houses the codebase for our user-friendly website, designed to simplify accommodation bookings. Explore seamless features, intuitive UI, and robust backend to elevate the hospitality experience. #HotelBooking #PGBooking #WebDevelopment 
# Figma Design of Website 

![website image ](https://github.com/anshul-gupta96/Smart-Stays/assets/113038747/f17f5e04-e2f8-4aef-861b-c523fb4090af)
# Tech Stack Used:

## Frontend:

- React (JavaScript library for building user interfaces)
- Tailwind CSS (CSS framework for styling)
- Stripe (for online payments)ff

## Backend:

- Node.js (JavaScript runtime for server-side development)
- Express.js (Web application framework for Node.js)
- MongoDB (NoSQL database for storing data)

## Testing:

• Automated tests for authentication, hotel features, search functionality, and booking

## Deployment:

• Deployment explained, likely using a platform like Heroku or similar services

# Overall Database Design:

The database design for the MERN stack Booking App likely involves MongoDB, a NoSQL database. Below are the key components and potential document structures:

## Users Collection:

Fields for user authentication, such as username, email, and password.
JWT tokens for secure authentication.

## Hotels Collection:

Information related to each hotel, including name, location, description, images, and other relevant details.
Possibly a reference or embedded documents for managing hotel owners.

## Bookings Collection:

Details of user bookings, including the hotel, check-in/out dates, and payment status.

## Search Terms Collection (Session Storage):

Storage for user search terms to enhance the user experience by providing recent searches.

## Other Collections:

Collections for additional features like recent hotels on the home page.

# Key Design Aspects:

## Authentication:

Secure authentication using HTTP cookies and JWT.

## Hotel Management:

CRUD operations for hotels, allowing users to add, edit, and view hotels.

## Image Uploads:

Integration of image uploads for hotels.

## Search, Sort, & Filter:

Implementation of functionalities to search, sort, and filter hotels.

## Online Payments:

Integration of Stripe for secure and efficient online payments during the booking process.

## Booking Management:

Features to view and manage bookings.

## Dynamic Content on Home Page:

Displaying recently added hotels on the home page for a dynamic and engaging user experience.
The overall design emphasizes building a comprehensive booking application with user authentication, hotel management, and various features to enhance user interaction and satisfaction. The use of the MERN stack ensures a robust and scalable architecture for web development.
