# React Google Maps Directions

This React application uses Google Maps API to calculate and display directions between two locations. It also shows the distance and duration of the route.

## Features

- **Google Maps Integration:** Utilizes the Google Maps JavaScript API for map rendering and directions calculation.
- **Autocomplete:** Provides autocomplete suggestions for location input.
- **Real-time Updates:** Dynamically updates the map, distance, and duration based on the selected origin and destination.
- **Clear Route:** Allows users to clear the route and input fields.
- **Responsive Design:** Responsive UI for optimal user experience.

## Getting Started


1. Install dependencies:  
   npm install
2. Set up your Google Maps API Key:

- Create a new project on the Google Cloud Console.
- Enable the "Directions API" and "Places API" for your project.
- Create API credentials and copy the API key.
- Create a `.env` file in the project root and add:

  REACT_APP_GOOGLE_MAPS_API_KEY=your-api-key

3. Run the application:
   
   npm start
   Open http://localhost:3000 in your browser.

   
## Features

- Enter the origin and destination locations in the input fields.
- Click "Calculate Route" to see the route on the map along with distance and duration.
- Click the "Clear Route" button to reset the map and input fields.

 # Dependencies

- React
- Chakra UI
- React Icons
- React Google Maps API
