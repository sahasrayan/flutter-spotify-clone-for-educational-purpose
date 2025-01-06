# Spotify Clone 🎵

A full-stack Spotify clone built using **Flutter** for the frontend, **FastAPI** for the backend, and **PostgreSQL** as the database. This project delivers a seamless music streaming experience with user authentication, playlist management, and much more.

## Features

### Frontend
- **Cross-Platform**: Developed with Flutter for Android, iOS, and Web.
- **State Management**: Efficiently handled using Riverpod.
- **Modern UI**:
  - Inspired by Spotify’s sleek design.
  - Smooth animations and intuitive user experience.
- **Key Functionalities**:
  - User authentication and profile management.
  - Browse and play songs, albums, and playlists.
  - Search for songs, artists, and albums.
  - Create and manage custom playlists.

### Backend
- **Fast and Scalable**: Powered by FastAPI for high-performance server operations.
- **RESTful APIs**: Provides endpoints for managing users, playlists, and songs.
- **Secure Authentication**: JWT-based authentication for secure access control.
- **Database**: Uses PostgreSQL for reliable and efficient data storage.

## Prerequisites

Before you begin, make sure you have the following installed:
- **Flutter SDK** (latest stable version)
- **Python 3.10+** for FastAPI
- **PostgreSQL**
- **Node.js** (optional, for managing assets)

## Installation

### Backend Setup
1. Navigate to the backend folder:
   ```bash
   cd server
2. Create and activate a virtual environment:
   ```bash
python -m venv env
source env/bin/activate  # For Windows: env\Scripts\activate
3. Install dependencies:
 ```bash
pip install -r requirements.txt
4.Set up the PostgreSQL database:
    Create a new database in PostgreSQL.
    Update the connection string in the .env file (refer to .env.example for guidance).
5.Start the FastAPI server:
 ```bash
    uvicorn main:app --reload
    The backend will be available at http://127.0.0.1:8000.
### Frontend Setup
6.Navigate to the frontend folder:
 ```bash
cd client
7.Install dependencies:
 ```bash
flutter pub get
8.Configure API endpoints:
Update the backend API URL in a constants file (e.g., lib/constants.dart) if necessary.
9.Run the Flutter app:
 ```bash
flutter run
