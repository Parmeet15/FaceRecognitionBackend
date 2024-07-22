# Face Recognition Backend

This project provides the backend for a face recognition application. It is built with Node.js and uses several controllers to handle different aspects of the application.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## Installation

1. Clone the repository:
    ```sh
    https://github.com/Parmeet15/FaceRecognitionBackend.git
    ```

2. Navigate to the project directory:
    ```sh
    cd FaceRecognitionBackend
    ```

3. Install the dependencies:
    ```sh
    npm install
    ```

## Usage

1. Start the server:
    ```sh
    npm start
    ```

2. The server will run on port 3000 by default. You can access it at `http://localhost:3000`.

## Project Structure
```sh
FaceRecognitionBackend-master
├── controllers
│ ├── image.js # Handles image-related operations
│ ├── profile.js # Handles profile-related operations
│ ├── register.js # Handles user registration
│ ├── signin.js # Handles user sign-in
├── package-lock.json # Lockfile for npm
├── package.json # Project metadata and dependencies
├── server.js # Main server file
└── README.md # Project documentation
```

### Controllers

- **image.js**: Contains logic for processing and analyzing images.
- **profile.js**: Manages user profiles and related data.
- **register.js**: Handles new user registrations, including validation and storage.
- **signin.js**: Manages user authentication and session handling.

## License

This project is licensed under the MIT License.

