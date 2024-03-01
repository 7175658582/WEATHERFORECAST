# Weather Forecast App

Welcome to the Weather Forecast App repository! This application provides real-time weather information using the OpenWeatherMap API. Whether you're a developer looking to integrate weather data into your project or just curious about the forecast, this app has you covered.

## Getting Started

### Prerequisites

To run the Weather Forecast App, ensure you have the following installed:

- **Node.js:** Make sure you have Node.js installed on your machine. You can download it [here](https://nodejs.org/).

### Installation

1. **Clone the Repository:**

   
   https://github.com/7175658582/weatherforecast
  

2. **Navigate to the Project Directory:**

   ```bash
   cd weather-forecast-app
   ```

3. **Install Dependencies:**

   ```bash
   npm install
   ```

4. **Set Up Environment Variables:**

   - Duplicate the `script.js` file and rename it to `.js`.
   - Obtain an API key from [OpenWeatherMap](https://openweathermap.org/api) and replace the placeholder in the `.js` file with your actual API key.

## Usage

### Running the App

1. **Start the Server:**

   ```bash
   npm start
   ```

2. **Make Requests:**

   Open your preferred API testing tool (such as Postman) and send GET requests to:

   ```
   http://localhost:3000/api/weather?city=yourcityname
   ```

   Replace `yourcityname` with the name of the city for which you want the weather forecast.

### Example Request

```http
GET /api/weather?city=London
```

### Example Response

```json
{
  "city": "London",
  "temperature": 18.5,
  "description": "Partly Cloudy",
  "humidity": 65,
  "windSpeed": 8.5
}
```

## Contribution

Contributions are welcome! If you'd like to enhance the Weather Forecast App, feel free to submit issues or pull requests. Follow the steps outlined in the [Contribution Guidelines](CONTRIBUTING.md).

## License

This Weather Forecast App is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it according to the terms of the license.

Happy forecasting! 🌦️
