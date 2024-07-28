# My Wish List App

## Overview

The My Wish List App is a simple Android application that allows users to manage their wish list items. It is built using Jetpack Compose and integrates with Room for local database management. The application features a basic UI for adding, editing, and deleting wishes, and utilizes modern Android development practices.

## Features

- **Home Screen**: Displays a list of all wishes with the ability to swipe to delete.
- **Add/Edit Wish**: Allows users to add new wishes or edit existing ones.
- **Navigation**: Uses Jetpack Compose's navigation component to switch between screens.

## Architecture

- **MVVM Pattern**: Utilizes the Model-View-ViewModel (MVVM) architecture to separate concerns.
- **Repository Pattern**: Encapsulates data operations within a repository.
- **Room Database**: Provides local storage for wishes.

## Project Structure

- `data/`: Contains data models, DAO interfaces, and the repository class.
- `ui/`: Contains composable functions for the user interface.
- `Navigation.kt`: Manages navigation between different screens.
- `MainActivity.kt`: Entry point of the application.

## Setup

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/mywishlistapp.git
