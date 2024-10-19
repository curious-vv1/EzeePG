# PG Management Website

This project is a **PG (Paying Guest) Management Website** that allows users to browse and book paying guest accommodations easily. It includes features for sorting PGs based on various criteria like rating, popularity, and cost. Additionally, users can filter PGs by city and category, with both user and admin panels for seamless management.

## Features

### User Panel
- **Sorting**: Users can sort PG listings based on:
  - Rating
  - Popularity
  - Cost (low to high, high to low)
- **Filtering**: Users can filter PGs by:
  - City
  - Category (e.g., Boys, Girls, Co-living, etc.)
- **Booking System**: Users can book PG accommodations through the website.
- **Authentication**: Secure sign-up and login system for users.
  
### Admin Panel
- **Authentication**: Admins have separate login access to manage the website.
- **Manage Bookings**: Admins can view and manage all bookings.
- **Change Booking Status**: Admins can update booking statuses (e.g., Confirmed, Cancelled, Completed).
- **Manage PG Listings**: Admins can add, edit, or delete PG listings.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/pg-management-website.git
    cd pg-management-website
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up environment variables**:
   Create a `.env` file and add the required environment variables for database connections and authentication keys.
   
4. **Run the project**:
    ```bash
    npm start
    ```

5. **Access the website**:
   The website will be running locally at `http://localhost:3000`.

## Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **State Management**: Redux
- **Form Handling**: react-hook-form
- **Backend**: json-server (for development, replace with actual backend)
- **Icons & UI**: @heroicons/react, @headlessui/react

## Admin Credentials

- Use the following credentials to log in as an admin for testing purposes:
  - **Username**: admin
  - **Password**: admin123

## Future Enhancements
- Add real-time messaging between users and PG owners.
- Implement a review and rating system for PG accommodations.
- Add payment integration for booking confirmations.

## Contributing

Contributions are welcome! Feel free to submit a Pull Request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
