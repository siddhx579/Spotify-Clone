# Spotify Clone

This is a full-featured responsive Spotify clone built using the MERN stack (MongoDB, Express.js, React, and Node.js). The project aims to replicate core Spotify functionalities, allowing users to browse, play, and manage music content in a seamless and interactive interface. The application is divided into three main modules:
- **Frontend**: The user-facing module where users can explore music and create playlists.
- **Backend**: The server-side API, music streaming, and database operations.
- **Admin**: An administrative dashboard to manage the music content and other configurations.

## Features
- Search and browse songs, albums, and artists
- Play, pause, and manage songs
- Admin panel for managing content
- Responsive UI

## Tech Stack
- **Frontend:** React, HTML
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

## Modules

### Frontend
- Developed with React to provide an intuitive user interface
- Includes components for playback, browsing, and user account management

### Backend
- Built with Express.js and Node.js
- Implements RESTful APIs for user authentication, song management, and search functionality

### Admin
- Admin dashboard to manage songs, albums
- Developed with React and protected routes for authorized access

## Installation

### Prerequisites
- Node.js and npm installed
- MongoDB database connection

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/siddhx579/Spotify-Clone.git
   cd Spotify-Clone

2. Set up environment variables:

  - Create .env files in each module directory (frontend, backend, admin).
  - Add necessary variables (e.g., database URI, Cloudinary API).

4. Install Dependencies:

   ```bash
   # Frontend
    cd Frontend
    npm install
    cd ..

   # Backend
    cd Backend
    npm install
    cd ..

   # Admin
    cd Admin
    npm install
    cd ..

6. Run the project:

   ```bash
   # Start Backend
    cd Backend
    npm run server

   # Start Frontend
    cd Frontend
    npm run dev

   # Start Admin
    cd Admin
    npm run dev

7. Access the application:
   - Frontend: http://localhost:5173/
   - Admin: http://localhost:5174/

8. Folder Structure:
   Spotify-Clone/
├── Frontend/        # React app for users
├── Backend/         # Express server with APIs
└── Admin/           # React app for admin management

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

