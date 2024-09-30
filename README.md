# HM-TravelSnap
**TravelSnap** is a travel journal platform where users can post, share, and recommend their travel experiences. It is built using the **MERN stack (MongoDB, Express, React, Node.js)** and offers a premium membership option for users who want additional features.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Technologies Used](#technologies-used)
- [Premium vs Free Accounts](#premium-vs-free-accounts)
- [Folder Structure](#folder-structure)
- [Usage](#usage)
- [License](#license)

## Features

- **Post and Share**: Users can share their travel experiences with posts containing text, images, and location data.
- **Recommendations**: Users can recommend places to visit based on their travel history.
- **Search & Filter**: Users can search for specific travel experiences or filter posts by destination, tags, or user.
- **Comment & Like**: Users can comment on and like posts to engage with others.
- **Profile Customization**: Users can personalize their profiles with travel stats and bio.
  
## Premium vs Free Accounts

### Free Accounts:
- Limited number of posts.
- Can view other users' posts.
- Can like and comment on posts.
- Access to basic travel recommendations and itineraries.

### Premium Accounts:
- **Unlimited posts**: Publish an unlimited number of travel experiences.
- **Book Publishing**: Premium users can compile their travel experiences into an e-book.

## Installation

### Prerequisites:
- Node.js
- MongoDB
- Git

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/TravelSnap.git
   cd TravelSnap
   ```

2. Install dependencies for the **client** and **server**:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

3. Set up environment variables in the **server** folder:
   - Create a `.env` file and add the necessary environment variables:
     ```bash
     MONGODB_URI=your-mongodb-uri
     JWT_SECRET=your-secret-key
     ```

4. Run both client and server:
   ```bash
   # Start the client (React app)
   cd client
   npm start

   # Start the server (Node.js + Express API)
   cd server
   npm start
   ```

5. Open the app at `http://localhost:3000`.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Authentication**: JWT (JSON Web Tokens)
- **Styling**: CSS, Bootstrap

## Folder Structure

```
TravelSnap/
│
├── client/   # Frontend (React)
│   └── src/
│       ├── components/   # React components
│       ├── pages/        # React pages (Home, Profile, etc.)
│       └── assets/       # Images, styles
│
└── server/   # Backend (Node.js, Express)
    ├── models/           # Mongoose models (User, Post, etc.)
    ├── routes/           # Express routes (API endpoints)
    └── controllers/      # Business logic for handling requests
```

## Usage

1. **Sign Up**: Users can sign up for a free account to share travel experiences.
2. **Upgrade to Premium**: Users can subscribe to premium features to unlock unlimited posts and other benefits.
3. **Create Posts**: Post your travel stories with images, text, and location data.
4. **Interact**: Like, comment, and engage with other users' posts.
