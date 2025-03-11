- # Historical Artifacts Tracker

- 🚀 **Client Repo**: [client-side](https://github.com/mehediNabil24/Artifacts-client-site)
- ⚡ **Server Repo**: [server-side](https://github.com/mehediNabil24/Artifacts-server-site)



## Project Overview
Historical Artifacts Tracker is a web application designed to help users browse, track, and contribute information about historical artifacts such as the Rosetta Stone, Antikythera Mechanism, and more. Users can view artifact details, add their own entries, and like artifacts. The application ensures an intuitive user experience while maintaining data privacy and security.

## Live URL
https://fardin-newspaper.web.app/

## Key Features
- **User Authentication:** Secure login and registration with email-password authentication and Google/GitHub authentication.
- **Artifact Management:** Users can add, view, update, and delete artifacts (CRUD operations).
- **Like System:** Users can like artifacts, and the like count updates dynamically.
- **Protected Routes:** Secure access to private routes using authentication.
- **Fully Responsive:** Works seamlessly on mobile, tablet, and desktop devices.
- **Modern UI/UX Design:** Eye-catching layout with proper alignment and color contrast.
- **Dynamic Page Titles:** Changes based on the current route.


## Technologies Used
### Frontend
- React.js
- React Router
- Tailwind CSS
- Firebase Authentication
- Axios
- React Toastify / SweetAlert

### Backend
- Node.js
- Express.js
- MongoDB (with Mongoose)
- JWT for authentication
- Dotenv for environment variable management

## Deployment
- **Frontend:** Deployed on Vercel/Netlify
- **Backend:** Deployed on Render/Heroku
- **Database:** Hosted on MongoDB Atlas

## Installation and Setup
### Prerequisites
- Node.js installed
- MongoDB configured (locally or on MongoDB Atlas)
- Firebase Project Setup

### Steps
1. Clone the repository:
   ```bash
   git clone [repository_url]
   cd historical-artifacts-tracker
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   - Create a `.env` file in the root directory and add:
     ```env
     REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
     REACT_APP_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Start the backend server:
   ```bash
   cd server
   npm install
   npm start
   ```

## Contribution Guidelines
- Make sure to include **at least 15 meaningful commits** on the frontend and **8 meaningful commits** on the backend with descriptive messages.
- Follow best coding practices and maintain code readability.
- Ensure full responsiveness and accessibility in UI design.

## Security Measures
- **Firebase Keys:** Secured using environment variables.
- **MongoDB Credentials:** Stored in environment variables.
- **JWT Implementation:** Ensures secure authentication and access control.

## Contact
For any issues or feature requests, feel free to raise an issue or contribute to the project!

---
Enjoy exploring historical artifacts with our web application!

