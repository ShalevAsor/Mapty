# Mapty Web App 

Welcome to the **Mapty - Activity Tracker Web App**! This application allows users to track and visualize their activities by adding markers on an interactive map. Built with modern JavaScript and Leaflet.js, it supports running and cycling workouts, capturing details such as distance, duration, and more.

## Features

- **Interactive Map**: Visualize your activities on an interactive map using Leaflet.js.
- **Activity Tracking**: Log running and cycling activities, including distance, duration, and specific metrics like cadence and elevation gain.
- **Custom Markers**: Add markers on the map for each activity, with custom pop-ups displaying detailed information.
- **Local Storage**: Save your activities in the browser's local storage to persist data across sessions.

## How It Works

1. **Add New Activity**:
   - Fill out the form to log a new activity, specifying the type (running or cycling), distance, duration, and other relevant details.
   - Click on the map to set the location for your activity.

2. **View Activities**:
   - All logged activities will be displayed as markers on the map.
   - Click on a marker to view details about the activity.

3. **Data Storage**:
   - Activities are stored in the browser's local storage and will be reloaded when you revisit the app.

## Code Overview

The app is built using the following classes:

- **`Workout`**: Base class for workouts, handling common functionality and properties.
- **`Running`**: Extends `Workout` for running activities, with additional calculations for pace.
- **`Cycling`**: Extends `Workout` for cycling activities, with additional calculations for speed.
- **`App`**: Manages the map, form interactions, and local storage.

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/activity-tracker.git

2. **Open the Project**:

Open index.html in your preferred web browser.


3. **Use the Application**:

Add new activities using the form.
View and interact with your activities on the map.

## Contributing
Feel free to contribute to the project by submitting pull requests or reporting issues. Your feedback and contributions are welcome!
