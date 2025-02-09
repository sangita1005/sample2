# Wanderlust

Wanderlust is a travel-related web application built using **Bootstrap**, **Node.js**, **Express.js**, and **MongoDB**.

## Features
- **User Authentication**: Sign up and login functionality for users.
- **Reviews**: Users can leave reviews on listings.
- **Admin Controls**: Admins can add, edit, or delete listings.
- **Map Integration**: Interactive Mapbox map to view listing locations.

## Technologies Used
- **Frontend**: 
  - HTML, CSS, JavaScript, EJS, Bootstrap
- **Backend**:
  - Node.js, Express.js, MongoDB
- **Libraries/Tools**:
  - passport.js (Authentication)
  - Mapbox (Map integration)
  - EJS (Templating views)
  
## Installation

   ```bash
   git clone https://github.com/dikshaa05/Wanderlust.git &&   cd dikshaa05-Wanderlust
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

