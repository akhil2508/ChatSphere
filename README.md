# ChatSphere

A modern real-time chat application built with React, Vite, and Firebase. ChatSphere provides users with a seamless messaging experience with user authentication, profile management, and real-time communication.

## Features

- **User Authentication**: Secure login and registration with Firebase Authentication
- **Real-time Messaging**: Send and receive messages instantly
- **User Profiles**: Create and update user profiles with avatars and personal information
- **Responsive Design**: Fully responsive UI that works on desktop, tablet, and mobile
- **Modern UI**: Clean and intuitive interface with sidebar navigation
- **Fast Performance**: Built with Vite for optimal development and production performance

## Tech Stack

- **Frontend Framework**: React 19
- **Build Tool**: Vite 7
- **Backend/Database**: Firebase 12
- **Routing**: React Router DOM 7
- **Notifications**: React Toastify 10
- **Styling**: CSS3
- **Linting**: ESLint 9

## Project Structure

```
src/
├── components/
│   ├── ChatBox/          # Chat message display and input component
│   ├── LeftSidebar/      # Navigation and contacts sidebar
│   └── RightSidebar/     # User info and settings sidebar
├── pages/
│   ├── Chat/             # Main chat interface
│   ├── Login/            # Authentication page
│   └── ProfileUpdate/    # User profile management
├── config/
│   └── firebase.js       # Firebase configuration
├── context/
│   └── AppContext.jsx    # Global state management
├── lib/
│   └── upload.js         # File upload utilities
├── assets/
│   └── assets.js         # Static assets and images
├── App.jsx               # Root component
├── main.jsx              # Application entry point
└── index.css             # Global styles
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager
- Firebase project with credentials

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ChatSphere.git
cd ChatSphere
```

2. Install dependencies:
```bash
npm install
```

3. Configure Firebase:
   - Create a Firebase project at [firebase.google.com](https://firebase.google.com)
   - Copy your Firebase configuration credentials
   - Update the configuration in `src/config/firebase.js`

4. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

## Available Scripts

- **`npm run dev`** - Start the development server with hot module replacement
- **`npm run build`** - Build the application for production
- **`npm run preview`** - Preview the production build locally
- **`npm run lint`** - Run ESLint to check code quality

## Firebase Setup

To use ChatSphere, you need to set up a Firebase project:

1. Go to [Firebase Console](https://console.firebase.google.com)
2. Create a new project
3. Enable Firestore Database
4. Enable Firebase Authentication (Email/Password)
5. Enable Firebase Storage (for profile images)
6. Copy your web app credentials and update `src/config/firebase.js`

## Development

The project uses:
- **Vite** for fast builds and HMR
- **React Router DOM** for client-side routing
- **Context API** for state management
- **Firebase SDK** for backend services

## Building for Production

```bash
npm run build
```

This generates an optimized build in the `dist` folder ready for deployment.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.

## Support

For issues, questions, or suggestions, please open an issue on the GitHub repository.
