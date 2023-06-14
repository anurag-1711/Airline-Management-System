# Airline Management System

## Description

Welcome to the repository for the Airline Management System. This project consists of multiple microservices developed using Node.js and Express.js within an MVC architecture. Each microservice handles specific functionalities of the system to ensure scalability, modularity, and robustness.

## Microservices

1. **Flight Service**: Responsible for managing flight, city, airport, airplane related operations such as creation, update, and deletion. Repository: [Flight Service Repository](https://github.com/anurag-1711/FlightsAndSearchService)
2. **Authentication Service**: Handles user authentication and authorization using JWT for secure login and bcrypt for password hashing. Repository: [Authentication Service Repository](https://github.com/anurag-1711/AuthService)
3. **Booking Service**: Handles the creation of bookings by fetching flight details, checking seat availability, calculating the total cost, and updating the database with the booking and flight information. Repository: [Booking Service Repository](https://github.com/anurag-1711/BookingService/)
4. **Reminder Service**: Sends notifications to users regarding flight updates, reminders, and important information using Nodemailer and Cron jobs. Repository: [Notification Service Repository](https://github.com/anurag-1711/ReminderService/)
5. **API Gateway**: Configured as a reverse proxy to provide a single entry point for client requests, enabling rate limiting and enhancing system security. Repository: [API Gateway Repository](https://github.com/anurag-1711/APIGateway)

## Getting Started

To run the microservices locally, follow the steps below:

1. Clone each microservice repository mentioned above using `git clone`.
2. Install the dependencies for each microservice using `npm install`.
3. Set up the necessary environment variables and configurations for each microservice as described in their respective README files.
4. Start each microservice individually by running `npm start`.

Please refer to the individual microservice repositories for more detailed instructions on setup, configuration, and usage.

## Contributing

I welcome contributions to enhance the functionality, performance, and overall quality of the backend microservices.

Feel free to modify this README file as per your project's specific requirements and structure. Make sure to provide clear instructions, documentation, and relevant links to the respective microservice repositories to help other developers understand and contribute to your project effectively.
