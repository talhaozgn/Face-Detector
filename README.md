# Face Detection React App

## Overview
This full-stack React application, developed as part of the "The Complete Web Developer in 2023: Zero to Mastery" course on Udemy, offers a unique functionality for detecting faces in images. Users can register, sign in, and use the app to detect faces in any image by providing its URL. The app highlights faces in the images with rectangles and keeps track of the number of images processed by each user, displaying this count on their profile.

## Features
User Authentication: Register and sign-in functionalities for personalized user experience.
Face Detection: Input an image URL and the app will detect faces within the image, highlighting them with rectangles.
Score Tracking: Each image processed increases the user's score, which is displayed on their profile.
Responsive Design: Optimized for various devices and screen sizes.

## Technologies Used
React.js for the frontend.
Node.js and Express.js for the backend server.
PostgreSQL for database management.
Clarifai API for face detection functionality.

## Installation and Setup
Clone the repository:
Install dependencies for both server and client.
Set up your PostgreSQL database and update the configuration.
Obtain an API key from Clarifai and configure it in the app.
Run the server and the client to start the application.

## Usage
After setting up:
Create an account and log in.
Enter the URL of an image with a human face.
The app will detect the face and display the image with a rectangle around it.
Each processed image increases your score, visible on your user profile.

## Contributing
Feel free to contribute to this project. You can fork the repository, add your features or improvements, and submit a pull request.

## Acknowledgements
Special thanks to the instructors and creators of "The Complete Web Developer in 2023: Zero to Mastery" on Udemy.
Clarifai API for providing the face detection functionality.
