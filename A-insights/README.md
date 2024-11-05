# A-Insights- Blog Mern application

## Overview

#problem statment
 Contributed to development of a MERN stack blog app with authentication, user profiles, real-time blog
management (create, update, delete, bookmark), user interactions (likes, comments, reviews), and search
functionality.



#Challenges
-Develop an AI-powered recommendation system for suggesting personalized blog posts based on user preferences and historical interactions.
-Implement advanced analytics and reporting functionalities to provide insights into user engagement, popular content, and trends.
-Enhance the real-time blog management system to support multimedia content (e.g., video posts, podcasts) with seamless upload and streaming capabilities.
-Integrate Redux for state management across the application, optimizing performance and scalability.
-Implement robust backend APIs to support complex user interactions such as nested comments, threaded discussions, and multi-level user permissions.

## Features

-Authentication system for secure user login and registration.
-User profile management with customizable settings and preferences.
-Real-time blog management functionalities including create, update, delete, and bookmark posts.
-Interactive user interactions such as liking posts, commenting, and leaving reviews.
-Advanced search functionality for discovering specific blog content.
-Integration of Redux for efficient state management between frontend and backend.
-Robust backend APIs for handling nested comments, threaded discussions, and user permissions management.

## Technologies Used

- **Frontend:** React.js, Axios, Redux
- **Backend:** Express.js(Node.js)
- **Database:** MongoDB
- **Authentication:** JSON Web Token (JWT)



## Demo

<a href='https://a-insights.onrender.com'> GO TO SITE ---> </a>

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB Atlas account for database access.
- React Developer Tools extension for an enhanced development experience (optional but recommended).

### Installation

1. **Clone the repository.**
   ```bash
   git clone git@github.com:Ashwanikumar1715/A-insights.git
   git clone git@github.com:Ashwanikumar1715/A-insights-api.git
   ```
2. **Navigate to the project directory.**

```
  cd A-insights
```

3. **Install dependencies for the frontend and backend..**

```
  cd frontend
npm install

cd ../backend
npm install
```

4. **Set up environment variables.**
   Create a .env file in the server directory.
   Add the following variables:

```
#  ---  Config.env  ---

NODE_ENV = development
PORT =5000
URI =backend link
MONGO_URI =
JWT_SECRET_KEY ='HOSDLKFSNCMCNNKC'
JWT_EXPIRE = 60m
RESET_PASSWORD_EXPIRE = 3600000 

# Nodemailer

SMTP_HOST =smtp.gmail.com
SMTP_PORT =587
EMAIL_USERNAME = 
EMAIL_PASS = 
```

5. **Run the development servers.**

```
 cd client
npm run dev

cd ../server
npm run dev
```

6. **Access the application in your browser at http://localhost:3000.**

## Contributing

We welcome contributions and ideas! Feel free to submit issues, feature requests, or even pull requests. For major changes, please open an issue first to discuss potential improvements.

## Future Development

AI-powered recommendation system for personalized blog post suggestions.
Analytics and reporting tools to track user engagement and content performance.
