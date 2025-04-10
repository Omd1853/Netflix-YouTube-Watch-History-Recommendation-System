# Netflix-YouTube-Watch-History-Recommendation-System
A C++ video streaming recommendation system with user management, built using OOP principles

Project Title : Advanced Video Recommendation System with User Management

Core Components :

Video Content Management :
Handles video metadata (title, genre, director, release year, duration)
Tracks view counts and maintains average ratings
Supports persistent storage of video catalog
User Management System :
Secure user authentication (login/signup)
Password hashing for basic security
Personalized watch history tracking
Video rating system (0-5 stars)
Recommendation Engine :
Dual recommendation strategies:
Genre-based suggestions using viewing history analysis
Top-rated recommendations based on community ratings
Intelligent content filtering
Dynamic recommendation updates based on user activity
Data Persistence :
File-based storage for video catalog
Automatic data saving on program exit
Support for loading/saving user data
Interactive CLI Interface :
Menu-driven navigation
Video browsing and selection
Rating system integration
Recommendation display
Key Features :

🎬 Content Catalog :
Stores video metadata
Maintains view statistics
Tracks community ratings
👥 User Accounts :
Secure login system
Personal watch history
Custom ratings profile
📊 Recommendation Algorithms :
Genre preference analysis
Weighted rating calculations
Hybrid recommendation approach
💾 Data Management :
CSV file storage for videos
Automatic state persistence
Data loading on startup
Implementation Details :

Class Architecture :

Video (Content Entity)
├── Metadata management
└── Rating/view tracking

User (Profile Entity)
├── Authentication
├── Watch history
└── Rating system

RecommendationEngine (Logic)
├── Genre-based recommendations
└── Rating-based recommendations

DataManager (Persistence)
├── File I/O operations
└── Data serialization

AuthService (Security)
├── Login system
└── Signup handler
