
# QuoraOfCollege

QuoraOfCollege is a web application designed to provide a platform for students and alumni to ask questions and share knowledge about various aspects of college life. The application aims to facilitate the exchange of information and experiences among college communities.

## Features

- **User Authentication**: Sign up, log in, and manage user profiles.
- **Ask Questions**: Users can post questions related to college life.
- **Answer Questions**: Users can provide answers to questions posed by others.
- **Vote System**: Users can upvote or downvote questions and answers.
- **Search Functionality**: Users can search for questions and answers using keywords.
- **Tags and Categories**: Organize questions by categories and tags for easy navigation.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, React (or any other frontend framework/library used)
- **Backend**: Node.js, Express (or any other backend framework/library used)
- **Database**: MongoDB, PostgreSQL (or any other database used)
- **Authentication**: Passport.js, JWT (or any other authentication method used)

## Installation

To run the project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Ajitcs-20/QuoraOfCollege.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd QuoraOfCollege
   ```

3. **Install dependencies:**

   For the frontend:

   ```bash
   cd frontend
   npm install
   ```

   For the backend:

   ```bash
   cd backend
   npm install
   ```

4. **Set up environment variables:**

   Create a `.env` file in the root directory of the backend project and add the necessary environment variables. For example:

   ```env
   MONGODB_URI=mongodb://localhost:27017/quoraofcollege
   JWT_SECRET=your_jwt_secret
   ```

5. **Run the application:**

   Start the backend server:

   ```bash
   cd backend
   npm start
   ```

   Start the frontend server:

   ```bash
   cd frontend
   npm start
   ```

   Open your browser and navigate to `http://localhost:3000` (or the appropriate port) to see the application in action.

## Usage

- **Register**: Create a new account or log in with existing credentials.
- **Ask Questions**: Use the "Ask Question" button to post new questions.
- **Answer Questions**: Navigate to a question and provide an answer.
- **Vote**: Upvote or downvote questions and answers based on their usefulness.
- **Search**: Use the search bar to find questions and answers quickly.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push them to your fork.
4. Submit a pull request with a description of your changes.

