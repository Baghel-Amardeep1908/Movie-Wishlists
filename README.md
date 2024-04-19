<!-- # React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh -->

# Movie Wishlists

Welcome to the Movie Wishlists project! This web application allows users to create and manage their own movie wishlists. Users can search for movies by title and add them to their wishlist for future streaming. The application provides a user-friendly interface with three main routes: Landing Page, User Dashboard, and Wishlist.

## Table of Contents

- [Getting Started](#getting-started)
- [Features](#features)
- [Routes](#routes)
  - [Landing Page](#landing-page)
  - [User Dashboard](#user-dashboard)
  - [Wishlist](#wishlist)
- [Technologies Used](#technologies-used)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

## Getting Started

To get started with this project, clone the repository to your local machine:

```bash
git clone https://github.com/Baghel-Amardeep1908/movie-wishlists.git

Navigate to the project directory:

bash
Copy code
cd Authenticate Assignment
Install the required dependencies:

bash
Copy code
npm install
Run the application using your preferred development server (e.g., npm start):

bash
Copy code
npm start
Features
User Authentication: Users can sign up and log in to the application.
Movie Search: Users can search for movies by title and view movie details.
Add to Wishlist: Users can add movies to their wishlist for future viewing.
View Wishlist: Users can view and manage their movie wishlist.
Routes
Landing Page
The Landing Page provides options for users to log in or sign up. Existing users can log in using their credentials, while new users can create an account. Once an account is created, user data is stored in local storage for future logins.

User Dashboard
The User Dashboard includes a search box where users can search for movies by title or name. Users can add movies to their wishlist for future streaming. Clicking on a movie poster will display the movie details.

There is also an account button that allows users to log out, redirecting them back to the Landing Page.

Wishlist
The Wishlist page displays the list of movies that the user has added to their wishlist. Users can view and manage their wishlist from this page.

Technologies Used
React: JavaScript library for building user interfaces.
Redux: State management library for handling application state.
React Router DOM: Library for routing in React applications.
Styled Components: Library for styling React components using CSS-in-JS.
Acknowledgments
The OMDb API for providing movie data.

Deployment
The application is deployed and can be accessed at: https://baghel-amardeep1908.github.io/movie-wishlists/

Contact
If you have any questions or feedback about the project, feel free to reach out to me at:

Email: baghel.amar1908@gmail.com
Thank you for checking out the Movie Wishlists project! I look forward to receiving your feedback and questions.
```