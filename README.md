# Weather-App
A backend service built with Node.js and Express.js to fetch and filter weather data for multiple cities.

Basic Architecture -
![image](https://github.com/AmaanAlii/Weather-App/assets/117629490/6025bb5d-ec85-462b-bce4-e84ffcd168ad)


## Features

- Retrieve weather data for multiple cities
- Filter data by city name or city code
- Support for pagination
- Detailed forecast for customizable number of days
- Filter data by city, date, or moment
- Retrieve current weather conditions of a specific city

## Technologies Used

- Node.js
- Express.js
- [Weather API Provider] (provide the name of the weather API service you are using)

## Getting Started

To get a local copy of the project up and running, follow these steps:

1. Clone the repository.

2. Install the dependencies.

3. Configure the environment variables:
- Rename the `.env.example` file to `.env`.
- Update the necessary environment variables with your API credentials or configurations.

4. Start the server

5. Access the application.


## API Endpoints

- `GET /weather` - Retrieves weather data of multiple cities (supports filtering and pagination)
- `GET /forecast/:days` - Retrieves detailed forecast for the next X days (replace `:days` with the desired number)
- `GET /weather/:city` - Retrieves current weather conditions of a specific city
- `GET /weather/:city/:date/:moment` - Retrieves weather data for a specific city, date, and moment

For detailed information about the API endpoints, parameters, and responses, please refer to the API documentation.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug fixes, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).


