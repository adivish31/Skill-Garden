# Skill Garden

A comprehensive online learning platform that connects educators and students, enabling course creation, enrollment, and progress tracking.

## Features

### For Students
- Browse and search courses
- Enroll in courses with payment integration
- Track learning progress
- Interactive course player
- User-friendly dashboard

### For Educators
- Create and manage courses
- Upload course content and materials
- Track student enrollments
- Monitor course performance
- Comprehensive dashboard

## Tech Stack

### Frontend
- **React.js** with Vite
- **Tailwind CSS** for styling
- Modern component-based architecture

### Backend
- **Node.js** with Express.js
- **MongoDB** for database
- **Cloudinary** for media storage
- **Multer** for file uploads
- **JWT** for authentication

## Project Structure

```
Skill-garden/
├── client/          # React frontend application
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   └── assets/
│   └── public/
└── server/          # Node.js backend application
    ├── configs/
    ├── controllers/
    ├── models/
    ├── routes/
    └── middlewares/
```

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Skill-garden.git
cd Skill-garden
```

2. Install dependencies for both client and server:
```bash
# Install root dependencies
npm install

# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install
```

3. Set up environment variables:
   - Create `.env` files in both client and server directories
   - Add necessary configuration (database URL, API keys, etc.)

4. Start the development servers:
```bash
# Start backend server
cd server
npm run dev

# Start frontend (in another terminal)
cd client
npm run dev
```

## Environment Variables

### Server (.env)
```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

### Client (.env)
```
VITE_API_URL=http://localhost:5000
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please reach out to [your-email@example.com]
