# JobQuest - Mobile Programming Project 2

## 📱 App Name
**JobQuest**

## 🎯 SDG Theme
**SDG 1: No Poverty**

> "End poverty in all its forms everywhere."  
> By providing access to employment opportunities, JobQuest helps individuals secure stable income and break the cycle of poverty. The app connects job seekers with employers, making it easier for people to find decent work and improve their livelihoods.

## 📋 Features

### Core Features
- 🔐 **User Authentication** - Login and Sign Up with local database storage
- 🏠 **Home Screen** - Overview of available jobs with personalized greeting
- 🔍 **Search Jobs** - Search by title, company, or location with live results
- 📍 **GPS/Location Sensor** - "Jobs Near You" feature using device GPS
- 📨 **Apply to Jobs** - Detailed application form with resume and cover letter
- 💾 **Local Persistence** - Room Database for offline access
- ☁️ **Cloud Sync** - Firebase Firestore for data backup and sharing
- 💬 **Chat with Employers** - Real-time messaging (saved to Firestore)
- ⭐ **Save Jobs** - Toggle save/unsave jobs to favourites
- 📅 **Job Fair Event** - RSVP and event details
- 🎨 **Dark/Light Theme** - Toggle between dark and light mode

### Technical Features
- **9 Screens** - Login, Sign Up, Home, Search, Profile, Details, All Jobs, Applied Jobs, Messages
- **Navigation** - Jetpack Navigation Compose with bottom navigation bar
- **State Management** - SharedViewModel with StateFlow
- **API Integration** - Retrofit with Apify API (JobStreet job listings)
- **Sensor Integration** - GPS/Location using Google Play Services

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Kotlin** | Programming language |
| **Jetpack Compose** | UI framework |
| **Jetpack Navigation** | Screen navigation |
| **Room Database** | Local data persistence |
| **Firebase Firestore** | Cloud data storage |
| **Retrofit** | REST API client |
| **Apify API** | JobStreet job listings |
| **Google Play Services** | GPS/Location sensor |
| **Coil** | Image loading from URLs |
| **Coroutines & Flow** | Asynchronous operations |

## 📸 Screenshots

*(Screenshots will be added soon)*

## 📂 Project Structure
app/src/main/java/com/example/a210813_izyani_drrimaniza_lab5/
├── MainActivity.kt # Main entry point
├── data/
│ ├── api/
│ │ └── ApiClient.kt # Retrofit API client
│ ├── firebase/
│ │ └── FirestoreService.kt # Firebase Firestore services
│ ├── AppDatabase.kt # Room Database
│ ├── AppliedJob.kt # Applied job data model
│ ├── AppliedJobEntity.kt # Room entity for applied jobs
│ ├── ChatModels.kt # Chat message and session models
│ ├── Converters.kt # Room type converters
│ ├── JobDao.kt # Room DAO for jobs
│ ├── JobListing.kt # Job listing data model
│ ├── JobRepository.kt # Repository for job data
│ ├── UserDao.kt # Room DAO for users
│ ├── UserEntity.kt # Room entity for users
│ ├── UserProfile.kt # User profile data model
│ ├── UserProfileEntity.kt # Room entity for user profile
│ └── UserRepository.kt # Repository for user data
├── screens/ # All Compose Screens
│ ├── AllJobsScreen.kt
│ ├── AppliedJobsScreen.kt
│ ├── AppliedPlaceholder.kt
│ ├── ApplyJobDialog.kt
│ ├── DetailsScreen.kt
│ ├── HomeScreen.kt
│ ├── LoginScreen.kt
│ ├── MessagesPlaceholder.kt
│ ├── ProfileScreen.kt
│ ├── SearchScreen.kt
│ ├── SharedViewModel.kt # Shared ViewModel with StateFlow
│ ├── SharedViewModelFactory.kt
│ └── SignUpScreen.kt
├── ui/theme/ # Theme Configuration
│ ├── Color.kt
│ ├── Theme.kt
│ └── Type.kt
└── utils/
└── LocationHelper.kt # GPS/Location helper class

## 🔧 Setup Instructions

### Prerequisites
- Android Studio Ladybug or later
- JDK 17+
- Android SDK 35

### Steps to Run

1. **Clone the repository**
```bash
git clone https://github.com/a210813/a210813_Izyani_DrRimaniza_Project2.git

## 📂 Project Structure
