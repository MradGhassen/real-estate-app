# Real Estate App

![Real Estate](https://i.ibb.co/jTW4bFC/image.png)

## Overview
Real Estate App is a comprehensive web application built with the MERN stack, enabling users to browse, search, and explore property listings. This project represents the culmination of my MERN stack development journey at Coding Dojo.

## Features
- **User Authentication:** Secure sign-up, login, and account management.
- **Property Listings:** Detailed property information, including descriptions, images, prices, and maps.
- **Search Functionality:** Intuitive search based on location, price range, property type, and more.
- **Property Details:** Comprehensive specifications, amenities, and seller/agent contact information.
- **Favorites:** Save favorite properties for future reference.
- **Contact Seller:** Direct communication with sellers or agents.
- **Admin Panel:** Dashboard for administrators to manage users, listings, and site settings.

## Technologies Used
- **Frontend:** React.js, Chakra UI, Next.js (optional for server-side rendering)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (with Mongoose ORM)
- **Authentication:** JSON Web Tokens (JWT), bcrypt.js (password hashing)
- **Deployment:** Heroku (backend), Vercel or Netlify (frontend), MongoDB Atlas (database hosting)

## Setup Instructions
1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/real-estate-app.git
    ```
2. **Install dependencies:**
    ```bash
    cd real-estate-app
    npm install   # for Node.js dependencies
    cd client
    npm install   # for React.js dependencies
    ```
3. **Configure environment variables:**
    - Create a `.env` file in the root directory and set environment variables like database connection URI, JWT secret key, etc.

4. **Run the development server:**
    ```bash
    npm run dev
    ```
5. **Access the application:**
    Open your web browser and navigate to [http://localhost:3000](http://localhost:3000) to view the application.

## Deployment
- **Backend (Node.js/Express.js):** Deploy to a platform like Heroku, ensuring proper environment variable setup.
- **Frontend (React.js):** Deploy to platforms like Vercel or Netlify, updating the API base URL to the deployed backend server.
- **Database (MongoDB):** Host the MongoDB database using MongoDB Atlas, updating the connection URI in the backend environment variables.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to contribute to the project.

## License
This project is licensed under the MIT License.

## Acknowledgements
Special thanks to Coding Dojo for providing the guidance and resources for developing this project.
