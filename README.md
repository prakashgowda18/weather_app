# Real-Time Weather Application

## Overview
This project constitutes an advanced, web-based real-time weather application designed to provide users with comprehensive meteorological data through a streamlined user interface. Users may input the name of a desired city into a search bar, and upon validation, detailed weather information is rendered. If the city is not found within the database, an explicit error notification is presented.

## Features
- **Intuitive Interface**: A meticulously designed interface that facilitates seamless user interaction.
- **City Query Functionality**: Enables users to conduct searches for any city by entering its name in the input field.
- **Robust Error Management**: Implements an effective feedback mechanism that informs users with a “No city found” message when a query fails to match.
- **Comprehensive Weather Metrics**: Upon successful verification, the application displays:
  - City name
  - Current temperature
  - Corresponding weather icon
  - Maximum and minimum recorded temperatures

## Technology Stack
- HTML,CSS and JavaScript
- **Data Source**: Open Weather API

## Functional Overview
1. **City Query Input**: Users initiate a search by entering the desired city in the search bar.
2. **Verification Process**: Upon the user’s action to search, the application cross-references the input against a database to confirm the city's existence.
3. **Error Handling Protocol**: If the inputted city does not match any entry, the system provides an error message, “No city found.”
4. **Weather Data Retrieval**: For valid entries, the application invokes the Open Weather API to display:
   - City name
   - Current temperature
   - A weather icon depicting current atmospheric conditions
   - Maximum temperature
   - Minimum temperature

## Installation and Setup
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/prakashgowda18/weather_app.git
   ```
2. Change directory to the project folder:
   ```bash
   cd weather-app
   ```
3. Install the required dependencies:
   ```bash
   npm install
   ```
4. Register for an account on [Open Weather](https://openweathermap.org/) and generate an API key.
5. Create a `.env` file in the project root and insert your API key:
   ```env
   REACT_APP_WEATHER_API_KEY=your_api_key_here
   ```
6. Launch the development server:
   ```bash
   npm start
   ```

## Usage Guidelines
- Enter the name of a city into the search bar.
- Click the **Search** button.
- If the city is validated, the application will display comprehensive weather data.
- If the city is not found, an informative message, “No city found,” will be shown.

## Contribution Guidelines
Contributions from the community are encouraged and appreciated. Interested developers may fork the repository and submit pull requests for review.

## Contact Information
For any inquiries or feedback, please contact prakashgowda2003@gmail.com.

---
We appreciate your interest in the Real-Time Weather Application.

