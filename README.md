# NexPathSA

## About the Project

**NexPathSA** is an Android application designed to help South African learners, matriculants, and students explore educational and career opportunities. The application brings information about bursaries, study programmes, careers, and application preparation together in one place.

It aims to help users make informed decisions about their education and future career paths.

## Key Features

- **User Accounts:** Register and sign in to access personalised features.
- **Bursary Opportunities:** Browse and search for bursaries and funding opportunities.
- **Career and Study Guidance:** Explore career paths, study programmes, and institutions.
- **Personalised Recommendations:** Receive recommendations based on user preferences and interests.
- **Saved Opportunities:** Save relevant opportunities and keep track of applications.
- **Academic Guidance:** Use subject marks and academic information to support study and career decisions.
- **CV and Documents:** Create a CV in PDF format and manage relevant documents.
- **Cloud Synchronisation:** Synchronise supported user information across devices.
- **Offline Storage:** Store application data locally using an SQLite database.

## Technologies Used

- **Java** – Android application development
- **XML** – User interface layouts
- **Android Studio** – Development environment
- **SQLite** – Local database and data storage
- **Firebase Authentication** – User authentication
- **Cloud Firestore and Firebase Storage** – Cloud data and document storage
- **External Data Sources** – Retrieve relevant bursary and qualification information

## Database

The application uses an SQLite database named `nexpathsa.db` to store and manage local application data, including user-related information, opportunities, saved items, and other application records.

**Database file:** [View nexpathsa.db](https://github.com/MolebohengMahahle/NexPathSA/blob/main/app/nexpathsa.db)
- To view the database, you need to download the raw db file and access it using an online database viewer: https://sqliteviewer.app/

## Requirements

- Android Studio
- JDK 17
- An Android device or emulator running Android 7.0 (API 24) or later
- Internet access for online features such as authentication, cloud synchronisation, and retrieving external information

## Getting Started

1. Clone or download this repository.
2. Open the project in Android Studio.
3. Allow Gradle to synchronise the project and download the required dependencies.
4. Run the application on a compatible Android device or emulator.

Some online features depend on the required Firebase configuration and an active internet connection.



---

*Developed as an academic capstone project focused on supporting educational and career guidance for South African learners and students.*
