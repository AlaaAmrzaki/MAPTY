# 🗺️ Mapty — Workout Tracker

A workout tracking application built with JavaScript that allows users to log running and cycling workouts on an interactive map.

## ✨ Features

- **Geolocation:** Display the map based on the user's current location.
- **Interactive Map:** Select a location on the map to add a workout.
- **Running Workouts:** Record distance, duration, and cadence.
- **Cycling Workouts:** Record distance, duration, and elevation gain.
- **Workout Statistics:** Automatically calculate running pace and cycling speed.
- **Workout List:** Display workout details in a list.
- **Map Markers:** Show workout locations on the map with descriptive popups.
- **Navigation:** Click a workout in the list to move the map to its location.
- **Data Persistence:** Save workouts in the browser's local storage.
- **Input Validation:** Validate workout inputs before saving them.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Object-Oriented Programming (Classes and Inheritance)
- DOM Manipulation
- Geolocation API
- Leaflet.js
- OpenStreetMap
- Local Storage
- Array Methods

## 🏃 Workout Types

### Running

Users can enter:
- Distance (km)
- Duration (minutes)
- Cadence (steps per minute)

The application calculates the running pace in minutes per kilometer.

### Cycling

Users can enter:
- Distance (km)
- Duration (minutes)
- Elevation gain (meters)

The application calculates the average cycling speed in kilometers per hour.

## 🚀 Getting Started

1. Clone or download this repository.
2. Open the project folder.
3. Open `index.html` in your browser.
4. Allow location access when prompted.
5. Click a location on the map to add a running or cycling workout.

**Note:** The project requires an internet connection to load map tiles from OpenStreetMap and requires browser geolocation support.

## 💾 Data Storage

Workout data is saved in the browser's `localStorage`, so workouts remain available after refreshing the page in the same browser.

## 📚 What I Learned

- Building applications using classes and inheritance.
- Managing application state with private class fields.
- Using `super()` to initialize parent class properties.
- Working with the Geolocation API.
- Integrating Leaflet.js for interactive maps.
- Handling form submissions and DOM events.
- Validating user input.
- Saving and restoring data with local storage.
- Working with arrays of objects.
- Separating application logic into reusable methods.

## ⚠️ Disclaimer

This is an educational project created for learning JavaScript. It is not intended to replace professional fitness tracking or navigation tools.

## 👨‍💻 Author

Created as a JavaScript learning project.
