# Weather API

This is a simple Weather API that provides weather information for a given location.

## Features

- Get current weather data
- Get weather forecast for the next 7 days
- Supports multiple locations

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/loneprog/Weather-api.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Weather-api
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

## Usage

1. Start the server:
    ```sh
    npm start
    ```
2. Make a request to the API:
    ```sh
    curl http://localhost:3000/weather?location=London
    ```

## Endpoints

- `/weather?location={location}`: Get current weather for the specified location
- `/forecast?location={location}`: Get 7-day weather forecast for the specified location

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please contact [wolfdon73@gmail.com](mailto:wolfdon73@gmail.com).