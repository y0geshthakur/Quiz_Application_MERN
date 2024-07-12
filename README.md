# Quiz Application MERN

This is a full-stack Quiz Application built using the MERN (MongoDB, Express, React, Node.js) stack.

## Features

- **User Authentication**: Users can sign up, log in, and log out securely.
- **Quiz Creation**: Admin users can create quizzes with multiple questions.
- **Taking Quizzes**: Users can take quizzes and submit their answers.
- **Real-time Results**: Users get their quiz results immediately after submission.
- **Responsive Design**: The application is fully responsive and works on all devices.

## Technology Stack

- **Frontend**: React.js, Redux for state management, CSS for styling.
- **Backend**: Node.js, Express.js for handling API requests.
- **Database**: MongoDB for storing user data and quiz information.
- **Authentication**: JSON Web Tokens (JWT) for secure authentication.
- **Deployment**: The application can be deployed using services like Heroku or Vercel.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/y0geshthakur/Quiz_Application_MERN.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Quiz_Application_MERN
    ```
3. Install the dependencies for both the server and client:
    ```bash
    cd server
    npm install
    cd ../client
    npm install
    ```
4. Set up environment variables:
    - Create a `.env` file in the `server` directory and add the following:
      ```env
      MONGO_URI=your_mongodb_uri
      JWT_SECRET=your_jwt_secret
      PORT=5000
      ```
5. Start the development server:
    - In the `server` directory, run:
      ```bash
      npm run dev
      ```
    - In the `client` directory, run:
      ```bash
      npm start
      ```

## Usage

- Visit `http://localhost:3000` to access the application.
- Sign up as a new user or log in with existing credentials.
- As an admin, create new quizzes.
- As a user, take available quizzes and view results.

## Contributing

Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## Contact

For any inquiries, please contact [Yogesh Thakur](work.yogeshthakur@gmail.com).

---

[GitHub Repository](https://github.com/y0geshthakur/Quiz_Application_MERN)
