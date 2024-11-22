
# Bookings Go Project

A reservation system built with Go and PostgreSQL, featuring secure user authentication and an admin management panel.

## Features

- **User Authentication**: Secure login and registration.
- **Bookings and Reservations**: Users can log in, book, and manage their reservations.
- **Admin Panel**: Admins can view, modify, and manage all reservations.
- **PostgreSQL Database**: Robust storage for user data and booking details.

## Tech Stack

- Backend: [Go](https://golang.org/)
- Database: [PostgreSQL](https://www.postgresql.org/)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MahdiKaseAtashin/bookings-go.git
   cd bookings-go
   ```

2. **Set up the database**:
    - Install PostgreSQL.
    - Create a database for the project.
    - Run the provided migration scripts (if available).

3. **Set up environment variables**:
   Create a `.env` file with the following:
   ```env
   DB_HOST=your_database_host
   DB_USER=your_database_user
   DB_PASSWORD=your_database_password
   DB_NAME=your_database_name
   JWT_SECRET=your_secret_key
   ```

4. **Install dependencies**:
   ```bash
   go mod tidy
   ```

5. **Run the project**:
   ```bash
   go run main.go
   ```

## Usage

- **Users**:
    - Register and log in.
    - Make and manage reservations.
- **Admins**:
    - Access an admin panel to view and modify all reservations.

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue.

## License

This project is licensed under the [MIT License](LICENSE).
