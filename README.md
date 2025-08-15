# My Workout & Nutrition Tracker

This is a simple, yet powerful, web-based application to track your workouts and nutrition. It's built with HTML, Bootstrap, and vanilla JavaScript, and it uses IndexedDB for client-side storage.

## Features

*   **Log Workouts**: Record your daily workouts, including exercises, sets, reps, and weight.
*   **Track Nutrition**: Log your daily caloric intake, as well as protein, carbohydrates, and fat.
*   **Body Weight**: Keep track of your body weight over time.
*   **Graph View**: Visualize your nutrition and exercise progress with interactive charts.
*   **Workout Templates**: Create and save workout templates for quick and easy logging.
*   **Personal Bests**: See your personal bests for each exercise.
*   **Export/Import Data**: Export your data to a JSON file for backup or to import it on another device.
*   **Responsive Design**: The application is fully responsive and works on all devices.

## How to Run

Since this is a client-side application, you can run it by simply opening the `index.html` file in your web browser. There is no need to install any dependencies or run any servers.

If you plan on hosting this on GitHub Pages, you can simply push the `index.html` file to a new repository and enable GitHub Pages in the repository settings.

## Implementation Details

The application is built using the following technologies:

*   **HTML**: The structure of the application is defined in the `index.html` file.
*   **Bootstrap**: The application is styled using the Bootstrap CSS framework.
*   **Vanilla JavaScript**: All of the application's logic is written in vanilla JavaScript.
*   **Chart.js**: The charts in the "Graph View" are created using the Chart.js library.
*   **date-fns**: The date-fns library is used for date manipulation.

## Data Storage

The application uses IndexedDB to store all of your data on the client-side. This means that your data is stored in your browser, and it will persist even if you close the browser or refresh the page.

The data is stored in two object stores:

*   **workouts**: This store contains all of your workout and nutrition data.
*   **templates**: This store contains all of your workout templates.

## Exporting and Importing Data

You can export all of your data to a JSON file by clicking the "Export Data" button in the "Log View". This will download a file called `my_workout_tracker_data.json` to your computer.

You can import data from a JSON file by clicking the "Import Data" button. This will open a file dialog where you can select the JSON file you want to import. The imported data will be added to your existing data.
