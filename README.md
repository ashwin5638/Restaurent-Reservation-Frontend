# Restaurant Reservation System - Frontend

A React-based frontend for the Restaurant Reservation Management System. It provides separate customer and administrator interfaces, allowing users to book tables, manage reservations, and securely interact with the backend REST API.

---

## Features

### Authentication

* User registration
* User login
* JWT-based authentication
* Role-based navigation
* Protected routes

### Customer Features

* View dashboard
* Create table reservations
* View reservation history
* Cancel reservations
* Responsive user interface

### Admin Features

* Admin dashboard
* View all reservations
* Filter reservations by date
* Update reservations
* Cancel reservations
* Manage restaurant tables

---

## Tech Stack

* React
* React Router DOM
* Axios
* Context API
* CSS

---

## Project Structure

```text
src/
│
├── api/
│   └── axios.js
│
├── assets/
│
├── components/
│   ├── Navbar/
│   ├── Footer/
│   ├── Loader/
│   ├── ReservationCard/
│   ├── ReservationForm/
│   ├── TableCard/
│   └── ProtectedRoute/
│
├── context/
│   └── AuthContext.jsx
│
├── hooks/
│   └── useAuth.js
│
├── layouts/
│   ├── CustomerLayout.jsx
│   └── AdminLayout.jsx
│
├── pages/
│   ├── Auth/
│   │   ├── Login.jsx
│   │   └── Register.jsx
│   ├── Customer/
│   └── Admin/
│
├── routes/
│   └── AppRoutes.jsx
│
├── services/
│   ├── authService.js
│   ├── reservationService.js
│   └── tableService.js
│
├── utils/
│
├── App.jsx
├── main.jsx
└── index.css
```

---

## Installation

Clone the repository.

```bash
git clone https://github.com/ashwin5638/RestaurentReservationSystem.git
```

Navigate to the frontend directory.

```bash
cd client
```

Install dependencies.

```bash
npm install
```

Start the development server.

```bash
npm run dev
```

The application will run at:

```text
http://localhost:5173
```

---

## Environment Variables

Create a `.env` file inside the `client` folder.

```env
VITE_API_URL=http://localhost:5000/api
```

---

## Main Pages

* Login
* Register
* Customer Dashboard
* Create Reservation
* My Reservations
* Admin Dashboard
* Reservation Management
* Table Management
* Page Not Found

---

## API Integration

The frontend communicates with the backend using Axios.

Example base URL:

```javascript
http://localhost:5000/api
```

---

## Future Enhancements

* Reservation calendar
* Search and filtering
* Dark mode
* Notifications
* Form validation improvements
* Responsive mobile design
* Loading skeletons

---

## Author

**Ashwin**

GitHub: https://github.com/ashwin5638
