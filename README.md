# Careerly

Careerly is a professional networking platform designed to enhance your career-building experience. Built with the MERN stack (MongoDB, Express.js, React, Node.js), Careerly offers a sleek and modern interface, delivering essential features for professional networking, such as connection management, real-time updates, and profile customization, with added functionalities for a personalized and engaging user experience.

## Features

### 1. **Connection Requests**

- Send and receive connection requests to grow your professional network.
- View pending requests and manage your connections seamlessly.

### 2. **Custom Notifications**

- Receive real-time notifications for connection requests, post engagements, and profile visits.
- Stay updated with alerts tailored to your activity.

### 3. **Personal Editable Profile**

- Create and customize your professional profile with ease.
- Add your photo, experience, skills, and more to showcase your expertise.

### 4. **Custom Posts Functionality**

- Share professional updates, articles, and achievements.
- Engage with others through likes, comments, and shares.

### 5. **Personal Welcome and Notification Emails**

- Receive a personalized welcome email upon signing up.
- Get notified via email for important activities, including connection requests and post interactions.

### 6. **Sleek and Modern Design**

- Enjoy an intuitive and visually appealing interface designed for productivity.
- Fully responsive for an optimal experience on any device.

## Technology Stack

Careerly is built using the MERN stack:

- **MongoDB:** Database for storing user data, posts, and notifications.
- **Express.js:** Backend framework for handling API requests and business logic.
- **React:** Frontend library for creating a dynamic and interactive user interface.
- **Node.js:** Runtime environment for server-side JavaScript execution.

## How to Run the Project

### Prerequisites

- Node.js (v14 or above).
- MongoDB instance (local or cloud-based).
- Environment variables setup (.env file for secrets like JWT keys, database URI, etc.).

## Installation

To run Careerly locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/careerly.git
   cd careerly
   ```

2. **Install dependencies:**

   ```bash
   # Install backend dependencies
   cd server
   npm install

   # Install frontend dependencies
   cd ../client
   npm install
   ```

3. **Set up environment variables:**

   - Create a `.env` file in the `server` directory using the env example file:

4. **Run the application:**

   ```bash
   # Start the backend
   cd server
   npm start

   # Start the frontend
   cd ../client
   npm start
   ```

5. **Access the application:**

   - Visit `http://localhost:3000` in your browser.

## Project Structure

```
  Careerly/
    |-- Server/        # Backend code (Node.js + Express)
    |-- Client/        # Frontend code (React.js)
    |-- .env.example   # Example environment variables
    |-- README.md      # Project documentation
```

## Deployment

- The application is deployed on Render.

## Demo

- You can access the demo of this project by clicking [here](https://talkifyin.netlify.app//)

## Screenshots

- Careerly Home Page
  ![Careerly homePage](https://i.imghippo.com/files/Jyf2150hw.png)

- Registration Page
  ![Registration Page](https://i.imghippo.com/files/vK5571G.png)

- Login Page
  ![Login Page](https://i.imghippo.com/files/ZE6842WiA.png)

- Connection requests Page
  ![Connection requests Page](https://i.imghippo.com/files/zD6515mS.png)

- Notifications Page
  ![Notifications Page](https://i.imghippo.com/files/tGM3373xg.png)

- Fully editable profile Page
  ![Fully editable profile Page](https://i.imghippo.com/files/tU7400YlQ.png)

## Future Enhancements

- Direct messaging between users.
- Advanced job search and application features.
- Skill endorsements and recommendations.
- Analytics for profile and post performance.

## Author

Developed with passion by [Uday Thakur](https://github.com/thaku7469 "Github Link"). Connect with me on [LinkedIn](https://www.linkedin.com/in/uday-thakur-7a835620a) or check out [my portfolio](https://www.linkedin.com/in/uday-thakur-7a835620a).

---

**Careerly: Your gateway to professional success.**