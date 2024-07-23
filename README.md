# Railway Reservation System

## Overview
This project is a Railway Reservation System designed and developed with two distinct modules: Admin and Passenger. The Admin module allows for managing train schedules, seat availability, and passenger records, while the Passenger module enables users to book, view, and cancel reservations.

## Features

### Admin Module
- **Train Schedule Management**: Add, update, and delete train schedules.
- **Seat Availability**: Manage and update seat availability for each train.
- **Passenger Records**: View and manage passenger booking records.

### Passenger Module
- **Booking Reservations**: Search for trains and book seats.
- **View Reservations**: View existing reservations and their details.
- **Cancel Reservations**: Cancel existing reservations and update seat availability.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Design**: Figma for initial design and prototyping

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo/railway-reservation-system.git
   ```

2. **Navigate to the Project Directory**
   ```bash
   cd railway-reservation-system
   ```

3. **Install Dependencies**
   ```bash
   npm install
   ```

4. **Set Up Environment Variables**
   - Create a `.env` file in the root directory.
   - Add the following environment variables:
     ```
     PORT=3000
     MONGODB_URI=your_mongodb_connection_string
     ```

5. **Run the Application**
   ```bash
   npm start
   ```

6. **Open in Browser**
   - Open your web browser and navigate to `http://localhost:3000`

## Usage

### Admin Module
1. **Login**
   - Admin users can log in with their credentials.
   
2. **Manage Train Schedules**
   - Add new train schedules, update existing ones, or delete them as necessary.

3. **Manage Seat Availability**
   - Update seat availability for each train based on bookings and cancellations.

4. **View Passenger Records**
   - View and manage records of all passengers who have made reservations.

### Passenger Module
1. **Registration and Login**
   - New users can register an account.
   - Existing users can log in with their credentials.

2. **Book Reservations**
   - Search for available trains.
   - Book seats on selected trains.

3. **View Reservations**
   - View details of current reservations, including train details and seat numbers.

4. **Cancel Reservations**
   - Cancel reservations and automatically update seat availability.

## Contributing
1. **Fork the Repository**
   - Click the "Fork" button on the repository's GitHub page.

2. **Create a New Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Your Changes**
   - Implement your feature or fix the bug.

4. **Commit Your Changes**
   ```bash
   git commit -am 'Add new feature'
   ```

5. **Push to the Branch**
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Create a Pull Request**
   - Go to the repository on GitHub and create a pull request.
