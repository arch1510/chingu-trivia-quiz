# Chingu Trivia Quiz App

The Chingu Trivia Quiz App is a web-based quiz application designed to test your knowledge across various topics. It offers an engaging and fun experience where users can challenge themselves with a series of multiple-choice questions. The app also includes a high score feature, allowing players to compare their performance with others.

**To Access the project's product backlog and user stories, click here:** https://www.notion.so/cbf46657bc5945f885f6fb85222686e3?v=5066c6709ad84610b5fa7c1e676177ff&pvs=4

## Purpose

The main purpose of the Chingu Trivia Quiz App is to provide an enjoyable and educational experience for users. It aims to:

- Offer a challenging quiz format that covers diverse topics.
- Encourage learning and exploration through interactive quizzes.
- Enable friendly competition by allowing users to compete for high scores.
- Showcase and develop web development skills for contributors.

## Major Functions

The Chingu Trivia Quiz App comes with the following key features:

1. Quiz Interface: The app provides an interactive quiz interface where users can answer multiple-choice questions related to various topics.

2. Scoring: Users earn points for each correct answer.

## Dependencies

The Chingu Trivia Quiz App relies on the following dependencies:

Backend team

- Node.js: The server-side JavaScript runtime used to run the application.
- Express.js: A popular web application framework for Node.js used to handle routing and server-side logic.
- MongoDB: A NoSQL database used to store high scores and user data.
- Mongoose: An object data modeling (ODM) library for MongoDB, used to interact with the database.

Design Team

- Figma: A UX/UI design tool to design the webpage.


Frontend Team

- NPM: The Node Package Manager, which manages the app's packages and dependencies.
- React.js: A JavaScript library for building user interfaces, used to create the front-end components of the app.

CI/CD Pipeline

- Github: For code review
- Jenkins: For Build and Deploy
- Godaddy: To create domain
- Heroku: To deploy

## Build and Deploy Instructions

To build and deploy the Chingu Trivia Quiz App, follow these steps:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/your-username/chingu-trivia-quiz-app.git
   ```

2. Navigate to the project directory:

   ```
   cd chingu-trivia-quiz-app
   ```

3. Install the required dependencies:

   ```
   npm install
   ```

4. Set up the MongoDB database: Ensure you have MongoDB installed and running. Update the database configuration in the app (e.g., server.js) to connect to your MongoDB instance.

5. Build the front-end: Run the following command to bundle the front-end React components:

   ```
   npm run build
   ```

6. Start the server: Run the following command to start the Node.js server:

   ```
   npm start
   ```

7. Access the app: Once the server is running, visit `http://localhost:3000` in your web browser to access the Chingu Trivia Quiz App.

## Contributing

We welcome contributions to improve the Chingu Trivia Quiz App. If you find any bugs, have feature requests, or want to add more questions to the quiz, please follow the contribution guidelines mentioned in the project's repository.

## License

The Chingu Trivia Quiz App is open-source software licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use, modify, and distribute the code as per the terms of the license.

## Acknowledgments

We want to thank all the contributors and community members who have helped make this app possible. Your efforts and support are greatly appreciated.

Enjoy playing the Chingu Trivia Quiz App! If you have any questions or feedback, please feel free to reach out to us.

Happy quizzing!
