# Quiz App

This project is a React-based quiz application, utilizing AWS Amplify for backend services & a CI/CD with GitHub . It was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). Users can sign in and take a quiz, with their scores calculated and displayed at the end.

## Features

- **Authentication:** Users can sign in or sign up using AWS Cognito.
- **Quiz Interaction:** Users can answer multiple-choice questions, receive immediate feedback, and view their total score at the end.
- **Responsive Design:** The UI is responsive and can be used on both desktop and mobile browsers.

## Getting Started

### Prerequisites

Before running the project, you will need:
- Node.js installed on your machine.
- An AWS account configured with the necessary services (Cognito, etc.) as per the `aws-exports.js` file.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/anthony-vlrd/amplify-cognito-quiz

2. Install the required dependencies:
   ```bash 
   npm install

3. Start the development server:
   ```bash
   npm start

This will run the app in development mode. Open http://localhost:3000 to view it in the browser.

### Built With
React - The web framework used.
AWS Amplify - For authentication and backend integration.
CSS - For styling components.
