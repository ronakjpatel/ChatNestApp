# ChatNest 🐦 🗣️

Chat Nest is a real-time chat application built using modern web technologies like React, TailwindCSS, Firebase, MongoDB, Node/Express, and Socket.io. It allows users to register/login, chat rooms, chat in real-time, update their profiles, and much more. ✨

![Screenshot](https://github.com/ronakjpatel/ChatNestApp/blob/07ff77009f36004253dcecea7cd5424a55bf6207/img1.png)

![Screenshot](https://github.com/ronakjpatel/ChatNestApp/blob/07ff77009f36004253dcecea7cd5424a55bf6207/img2.png)

## Technologies Used

- React and TailwindCSS for the frontend
- Firebase for authentication
- Node/Express for creating API endpoints
- MongoDB for storing chat room members and their messages
- Socket.io for making the app real-time

## Basic Features 🚀

- Users can register/login via email and password.
- Profile page where users can update their avatar and display name.
- Generate random avatars using [DiceBear API](https://avatars.dicebear.com/docs/http-api)
- Users can create a room to chat with others.
- Users can see online status.
- Search functionality.
- Chatting is real-time.
- Emoji picker is also integrated.
- Dark mode can be enabled.

## Getting Started 🏁

To run this project locally, follow these steps:

1. Clone the repository.
2. Install the dependencies:
   - Navigate to the `frontend` directory and run `npm install`.
   - Navigate to the `server` directory and run `npm install`.
3. Set up Firebase:
   - Go to the [Firebase Console](https://console.firebase.google.com/).
   - Create a new project or select an existing one.
   - Go to the project settings or service accounts section.
   - Click on "Generate new private key" or a similar option.
   - Save the downloaded JSON file as `serviceAccountKey.json`.
   - Place the downloaded `serviceAccountKey.json` file in the `server/config` directory.
4. Set up Environment Variables:
   - In the `frontend` directory, create a new file named `.env` based on the `.env.example` file.
   - Update the values of the environment variables in the `.env` file with your Firebase configuration details.
   - In the root directory, create a new file named `.env` based on the `.env.example` file.
   - Update the values of the environment variables in the `.env` file according to your preferences. For example, set the `PORT` variable to specify the desired port for the server and set `MONGO_URI` to your MongoDB connection URI.
5. Run the server:
   - Navigate to the `server` directory and run `npm run start`.
6. Run the client:
   - Navigate to the `frontend` directory and run `npm start`.
7. The application will be accessible at `http://localhost:3000`.


Enjoy chatting with Chat Nest! 🐦🌟

📝 Note
Please make sure to keep the `serviceAccountKey.json` file and sensitive information secure and not commit them to version control.

## 📸 Some Glimpse

![Screenshot](https://github.com/ronakjpatel/ChatNestApp/blob/07ff77009f36004253dcecea7cd5424a55bf6207/demo_gif_1.gif)


![Screenshot](https://github.com/ronakjpatel/ChatNestApp/blob/07ff77009f36004253dcecea7cd5424a55bf6207/demo_gif_2.gif)

