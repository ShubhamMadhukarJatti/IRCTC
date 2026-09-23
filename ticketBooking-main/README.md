

# IRCTC Backend Project

## Project Overview

The IRCTC Backend Project is a Java based application designed to simulate a real-world train booking system. It supports user sign-up, login, fetching bookings, searching for trains, booking seats, and canceling bookings.

## Features

1. **User Signup**: New users can create an account by providing a username and password.
2. **User Login**: Existing users can log in to their accounts.
3. **Fetch Bookings**: Users can retrieve their current bookings.
4. **Search Trains**: Users can search for trains between two stations.
5. **Book a Seat**: Users can book a seat on a selected train.
6. **Cancel Booking**: Users can cancel their bookings.
7. **Exit**: Users can exit the application.

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- An Integrated Development Environment (IDE) like IntelliJ IDEA or Eclipse
- Internet connection (for Maven dependencies)

## Project Structure

- `App.java`: The main entry point of the application.
- `entities/Train.java`: Represents the Train entity.
- `entities/User.java`: Represents the User entity.
- `entities/Ticket.java`: Represents the Ticket entity.
- `services/UserBookingService.java`: Provides services for user operations like sign-up, login, booking, etc.
- `services/TrainService.java`: Provides services for train operations like add train, update train, etc.
- `util/UserServiceUtil.java`: Contains utility methods for user services.

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/ShubhamMadhukarJatti/IRCTC.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd irctc-backend
    ```

3. **Open the project in your IDE**:

    - Open your preferred IDE.
    - Import the project as a Maven project.

4. **Build the project**:

    - In your IDE, build the project to resolve all dependencies.

## Running the Application

1. **Run `App.java`**:

    - In your IDE, navigate to the `App.java` file.
    - Right-click and select `Run 'App.main()'`.

2. **Interacting with the Application**:

    - Follow the on-screen prompts to sign up, log in, search for trains, book seats, and manage your bookings.

## Usage

1. **Sign Up**:

    - Select option `1` to sign up.
    - Enter a username and password to create a new account.

2. **Login**:

    - Select option `2` to log in.
    - Enter your username and password to access your account.

3. **Fetch Bookings**:

    - Select option `3` to fetch your current bookings.

4. **Search Trains**:

    - Select option `4` to search for trains.
    - Enter the source and destination stations.

5. **Book a Seat**:

    - Select option `5` to book a seat.
    - Select a train and choose a seat from the available options.

6. **Cancel Booking**:

    - This feature is to be implemented. Currently, users can manage bookings via the provided options.

7. **Exit**:

    - Select option `7` to exit the application.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code adheres to the coding standards and includes relevant tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any queries or issues, please contact [shubhamjatti01@gmail.com].

---

Thank you for using the IRCTC Backend Project! Enjoy your train booking experience.
