🎬 Reel Desk – Movie Ticket Booking System

Reel Desk is a simple and interactive movie ticket booking web application built using HTML, CSS, and JavaScript.

It allows users to browse movies, view showtimes, select seats, confirm bookings, and manage their booked tickets. An Admin section is also included for adding movies and scheduling showtimes.

✨ Features

🎥 Movie Browsing

- View currently available movies
- Search movies by title or genre
- Display movie genre, duration, rating, and number of showtimes
- View movie description and available showtimes

🎟️ Ticket Booking

- Select a preferred showtime
- Interactive seat selection
- 8 rows with 10 seats per row
- Shows available, selected, and already-booked seats
- Automatically calculates the total ticket price
- Generates a unique booking code after confirmation

📋 My Bookings

- View all confirmed bookings
- See movie name, date, time, selected seats, and total price
- Cancel an existing booking
- Cancelled seats become available again

⚙️ Admin Panel

- Add new movies
- Enter movie genre, duration, rating, poster color, and synopsis
- Add showtimes with date, time, and ticket price
- Delete movies
- View the number of scheduled showtimes

💾 Local Storage

The application uses the browser's localStorage to store:

- Movie information
- Showtimes
- Booked seats
- User bookings

Therefore, data remains available when the page is refreshed on the same browser/device.

🛠️ Technologies Used

- HTML5 – Structure of the application
- CSS3 – Styling and responsive layout
- JavaScript – Application logic and interactions
- LocalStorage – Client-side data persistence
- Google Fonts – Inter and Bebas Neue fonts

📂 Project Structure

Reel-Desk/
│
└── index.html

The complete application is currently implemented in a single "index.html" file containing the HTML structure, CSS styling, and JavaScript functionality.

🚀 How to Run

1. Download or clone this repository.
2. Open the project folder.
3. Open "index.html" in any modern web browser.
4. Start browsing movies and booking seats.

No server or database setup is required.

🎯 Application Flow

Browse Movies
      ↓
Select Movie
      ↓
View Showtimes
      ↓
Select Seats
      ↓
Confirm Booking
      ↓
My Bookings
      ↓
View / Cancel Booking

👨‍💻 Admin Flow

Admin Panel
     ↓
Add Movie
     ↓
Select Movie
     ↓
Add Date & Time
     ↓
Set Ticket Price
     ↓
Schedule Showtime

📌 Sample Movies

The application comes with sample movies such as:

- Nightfall Junction – Thriller
- The Last Orchard – Drama
- Ion Drift – Sci-Fi
- Paper Tigers – Comedy

Sample showtimes and booked seats are included for demonstration purposes.

🔮 Future Enhancements

Possible improvements for future versions:

- User login and registration
- Online payment integration
- Backend database
- Real-time seat availability
- Movie poster images
- Email/SMS booking confirmation
- QR-code ticket generation
- User profiles and booking history
- Secure admin authentication
- Responsive mobile application

📄 License

This project is created for educational and project demonstration purposes.
