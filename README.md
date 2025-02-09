# Wanderlust

Wanderlust is a travel-related web application that allows users to post reviews, and manage their user profiles. Built using **Bootstrap**, **Node.js**, **Express.js**, and **MongoDB**, it provides a dynamic and interactive platform to plan and share travel experiences.

## Features
- **User Authentication**: Sign up and login functionality for users.
- **Reviews**: Users can leave reviews on listings.
- **Admin Controls**: Admins can add, edit, or delete listings.
- **Map Integration**: Interactive **Mapbox** map to view listings locations.

## Technologies Used
- **Frontend**: 
  - HTML, CSS, JavaScript, EJS, Bootstrap
- **Backend**:
  - Node.js, Express.js, MongoDB
- **Libraries/Tools**:
  - bcryptjs (for hashing passwords)
  - passport.js (for authentication)
  - Mapbox (for map integration)
  - EJS (for templating views)
  
## Installation

   ```bash
   git clone https://github.com/yourusername/dikshaa05-Wanderlust.git &&   cd dikshaa05-Wanderlust
   ```
   ```
   npm install
   ```
**If you're using MongoDB locally, make sure it is running.**
**If you're using MongoDB Atlas, create a `.env` file and add your MongoDB URL.**

   ```
   npm start
   ```
   The app will be live on `http://localhost:3000`.

## Usage
- Navigate to `http://localhost:3000` to access the application.
- Users can view listing details, and add reviews.
- Admins can log in to manage the listings.
- The interactive map helps users locate listings easily.

