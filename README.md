# PlacePicker

PlacePicker is a React application that allows users to create a personal collection of places they would like to visit or have already visited. It uses geolocation to sort available places by distance from the user.

## Features

- Displays a list of available places sorted by distance.
- Allows users to select places from a list.
- Stores selected places in localStorage for future use.
- Modal for confirming the removal of selected places.

## Screenshot

![PlacePicker Screenshot](https://github.com/macettiandrea/React-Favorite-Places/blob/master/Screenshot/Screenshot.png)

## Technologies Used

- React
- Vite
- LocalStorage
- CSS

## Installation Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/macettiandrea/React-Favorite-Places.git

   ```

2. Navigate into the project directory:

   ```bash
   cd React-Quiz-App
   ```

3. Install all the dependencies using NPM:

   ```bash
   npm install
   ```

4. Run the app in development mode:

   ```bash
   npm run dev
   ```

5. Open [http://localhost:5173](http://localhost:5173) to view the app in your browser.

## File Structure

    src/
        App.jsx: Main application component.
        components/
            Places.jsx: Displays the list of places.
            Modal.jsx: Modal component for confirmation dialogs.
            DeleteConfirmation.jsx: Confirmation dialog for deleting a place.
            ProgressBar.jsx: Shows a progress bar for the delete confirmation timer.
        data.js: Contains available places data.
        loc.js: Utility functions for sorting places by distance.
        assets/: Contains images and other static assets.

## Usage

    Upon loading, the application will request permission to access your location.
    You can select places you'd like to visit or have visited.
    To remove a place, click on it, and confirm the removal in the modal that appears.

## License

This project is licensed under the MIT License.
