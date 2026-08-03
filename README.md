# JavaScript-Doctor-appointment-booker
A simple Doctor Appointment Booking form built with HTML, CSS, and vanilla JavaScript. Validates appointment time and prevents booking outside doctor availability hours (10 AM–10 PM).
# Doctor Appointment Booking Form

A simple front-end web app for booking doctor appointments, built using plain **HTML**, **CSS**, and **vanilla JavaScript** (DOM manipulation only — no frameworks or libraries).

## Features

- Simple booking form with fields for:
  - Patient Name
  - Phone Number
  - Appointment Date
  - Appointment Time
- Time validation using JavaScript:
  - Doctor is available only from **10:00 AM to 10:00 PM**
  - If a user selects a time outside these hours, the booking is rejected with an alert message
- Confirmation message displayed on successful booking
- Clean, card-style UI with basic CSS styling

## How It Works

1. User fills out the form and clicks **Book Appointment**.
2. The `bookAppointment()` JavaScript function runs on form submission.
3. The selected time is checked against the doctor's available hours.
4. - If the time is **not available**, an alert is shown and the booking is blocked.
   - If the time is **available**, a success message is displayed with the booking details.

## Tech Stack

- HTML5
- CSS3 (inline `<style>` block)
- JavaScript (vanilla, DOM-based — `getElementById`, `.value`, `.innerHTML`, inline event handlers)

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/doctor-appointment-booking.git
   ```
2. Open `index.html` in any web browser.
3. Fill in the form and try booking an appointment inside and outside the available hours to see the validation in action.

## Project Structure

```
doctor-appointment-booking/
│
├── index.html      # Main HTML file with form, CSS, and JS
└── README.md        # Project documentation
```

## Future Improvements

- Connect to a backend server to store bookings in a database
- Add doctor availability by date (not just fixed hours)
- Add form validation for empty fields and phone number format
- Allow multiple doctors with individual schedules

## Author

Built as a practice project while learning front-end web development.
