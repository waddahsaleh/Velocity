# Velocity: Car Marketplace Moblie Application
## Overview

In response to the need for a modern, user-friendly platform for buying and selling vehicles, we present this proposal for the development of a Car Marketplace Application. This app will provide a feature-rich and interactive experience for both buyers and sellers of automobiles.

This Android application serves as a comprehensive car marketplace allowing users to buy and sell cars. It offers functionalities for user authentication, profile management, car listings, map integration, and more.

## Features

### Authentication
- **Signup**: Users can register using their email, password, first name, last name, phone number, and address.
- **Login**: Existing users can sign in to access the application's features.

### Profile Management
- **Profile Viewing**: Users can view their profile information (first name, last name, email, phone number).
- **Profile Editing**: Users can edit their profile details and save changes.
- **Profile Image**: Includes functionality to set a profile image using Glide (commented out in code).

### Marketplace Listings
- **Car Listings**: Displays car listings retrieved from Firebase Firestore.
- **Listing Details**: Each listing includes car make, model, year, odometer reading, and price.
- **Listing Interaction**: Handles item click events for individual car listings.

### Map Integration
- **Google Maps**: Integrates Google Maps to display user location or specified addresses.
- **Location Permissions**: Requests and handles user location permissions.

### Other Components
- **ViewModel Architecture**: Utilizes ViewModel for shared data between fragments or activities.
- **Shared Data**: Manages shared data like car listings, user profiles, and image sources using LiveData.
- **Splash Screen**: Redirects users to the main activity or login/signup screen based on authentication status.

## Setup Instructions
1. **Clone Repository**: Clone this repository to your local machine.
2. **Setup Firebase**: Set up Firebase for authentication and Firestore. Add `google-services.json` to the app module.
3. **Android Studio**: Open the project in Android Studio and sync Gradle files.
4. **Run the App**: Run the application on an emulator or physical device.

## Usage
- **Signup/Login**: Register or sign in to access the application.
- **Profile**: View/edit your profile information.
- **Car Listings**: Browse available car listings.
- **Map**: Explore the map feature (if applicable).

## Technologies/Frameworks Used
- Android Studio
- Firebase (Authentication, Firestore, Cloud Storage)
- Google Maps API
