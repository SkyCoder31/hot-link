Full Stack Dating Web Application


A dating web application where users can sign up/login with their email and password, upload their own image, and scroll through other users' images.


Features

UI
Sign up/login with email and password
Upload one image for each user
User interface to scroll random images
Logged-in users can scroll images and perform the following actions:
Like
Block
Superlike
Backend
Test users loading: Pre-loaded with 10 images in the database
Sign up API: Basic email and password-based registration
Login API: JWT-based login with email and password
Image like API: When a user likes another user's image, a socket io notification will be sent to the other user. The image of the person who liked will not be visible to the user being liked.
Image superlike: When a user superlikes another user's image, a socket io notification will be sent to the other user, and the image of the person who liked will be visible to the user being liked.
Block API: When a user blocks another user, their image will not be shown while the blocked user is scrolling through random images.
Technical Requirements
The application is built with a combination of React for the frontend and Node.js/Express for the backend. The database is managed with MongoDB, and socket io is used for real-time notifications.

Getting Started
Clone the repository to your local machine
bash
Copy code
git clone https://github.com/<your-username>/full-stack-dating-app.git
Install the necessary dependencies
  
  
Copy code
npm install
Start the application
sql
Copy code
npm start
The application should now be running on http://localhost:3000.

Contributing
Contributions are welcome! Please feel free to open an issue or submit a pull request if you have any suggestions or bug fixes.
