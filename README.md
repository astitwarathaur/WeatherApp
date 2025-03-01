# Weather App

This is a simple weather application built using HTML, CSS, and React.js. It allows users to search for a city and view the current weather conditions, including temperature, humidity, wind speed, and a brief description.

## Features

* **City Search:** Users can enter a city name to retrieve weather information.
* **Current Weather Display:** Displays the current temperature, weather description, humidity, and wind speed.
* **Responsive Design:** Adapts to different screen sizes for optimal viewing on various devices.

## Technologies Used

* **React.js:** For building the user interface and managing application state.
* **HTML:** For structuring the application's content.
* **CSS:** For styling the application.
* **OpenWeatherMap API:** For fetching weather data.

## Prerequisites

Before running the application, ensure you have the following installed:

* **Node.js:** (https://nodejs.org/)
* **npm (Node Package Manager) or yarn:** (npm is included with Node.js, yarn: https://yarnpkg.com/)
* An API key from OpenWeatherMap (https://openweathermap.org/api). You will need to create a free account and generate an API key.

## Installation

1.  **Clone the repository:**

    ```bash
    git clone [repository URL]
    cd weather-app
    ```

2.  **Install dependencies:**

    ```bash
    npm install  # or yarn install
    ```

3.  **Add your OpenWeatherMap API key:**

    * Create a `.env.local` file in the root directory of the project.
    * Add your API key to the `.env.local` file:

        ```
        REACT_APP_API_KEY=YOUR_API_KEY
        ```

        Replace `YOUR_API_KEY` with your actual API key.

4.  **Start the development server:**

    ```bash
    npm start  # or yarn start
    ```

    The application will open in your default browser at `http://localhost:3000`.

## Building for Production

To create a production build of the application:

```bash
npm run build  # or yarn build
