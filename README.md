# Firebase + TypeScript + Realtime Database for Journaling Web App

This project is a journaling web application built using Firebase, TypeScript, and Firebase Realtime Database. It provides a platform for users to securely log their thoughts, feelings, and experiences in real-time.

## Features

- **User Authentication**: Secure user authentication using Firebase Authentication.
- **Real-time Updates**: Utilizes Firebase Realtime Database to provide real-time updates and synchronization across multiple devices.
- **TypeScript**: The project is written in TypeScript, providing type safety and enhanced developer experience.
- **Journal Entries**: Users can create, read, update, and delete journal entries.
- **Responsive Design**: The web application is designed to be responsive, ensuring a seamless experience across various devices.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/KellyDanielO/todays_journal_web.git
```

2. Navigate to the project directory:

```bash
cd todays_journal_web
```

3. Install dependencies:

```bash
npm install
```

4. Set up Firebase:
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Enable Firebase Authentication and Firebase Realtime Database.
   - Obtain your Firebase configuration (apiKey, authDomain, projectId, etc.) from the Firebase console.
   - Add the Firebase configuration to `src/firebaseConfig.ts` file.

5. Run the project:

```bash
npm start
```

6. Open your web browser and visit `http://localhost:3000` to view the application.

## Contributing

Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/MyFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/MyFeature`).
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
