# Project Name
Booking_table_on_Little-Lemon_Restaurant

## Overview
This project is a frontend web application focused on delivering a seamless and user-friendly UI/UX experience. It utilizes `React` and `react-router-dom` to create a structured and navigable single-page application (SPA). The application features multiple pages and a layout component to maintain consistent design and usability throughout the app.

## Features
- **Home Page**: The primary landing page of the application.
- **Bookings Page**: A page for managing bookings.
- **Confirmed Booking Page**: Displays confirmation details for bookings.
- **Under Construction Pages**: Placeholder pages for sections currently under development, such as About, Menu, Order Online, and Login.
- **404 Not Found Page**: A fallback page displayed when a user navigates to an undefined route.

## Tech Stack
- **React**: A JavaScript library for building user interfaces.
- **React Router**: For managing client-side routing and navigation.
- **JavaScript (ES6+)**: For writing clean and modular code.
- **HTML & CSS**: For structuring and styling the application.

## File Structure
```
├── src
│   ├── components
│   │   ├── layout
│   │   │   └── Layout.js      # Layout component for consistent design
│   │   ├── pages
│   │   │   ├── Home        # Home page component
│   │   │   ├── Bookings    # Bookings page component
│   │──────index.css
│   │──────index.js
│   │   │   ├── NotFound   # 404 Not Found page
│   │   │   └── UnderConstruction # Placeholder for under-development pages
│   ├── utils
│   │   └── pages.js             # Map of routes and paths
│   └── App.js
                  # Root component with routing logic
```

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd Booking_table_on_Little-Lemon_Restaurant
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
5. Open the app in your browser at `http://localhost:3000`.

## Usage
- Navigate through the pages using the provided links in the layout.
- Interact with the Home and Bookings pages for a functional experience.
- Note that some pages (About, Menu, Order Online, Login) are placeholders and display an "Under Construction" message.
- Use an undefined URL to see the 404 Not Found page.

## Routing Configuration
The `pages.js` utility is a central configuration for managing routes and their corresponding paths. This approach ensures scalability and ease of maintenance.

### Example from `pages.js`:
```javascript
const pages = new Map([
  ['home', { path: '/' }],
  ['about', { path: '/about' }],
  ['menu', { path: '/menu' }],
  ['bookings', { path: '/bookings' }],
  ['confirmedBooking', { path: '/bookings/confirmed' }],
  ['orderOnline', { path: '/order-online' }],
  ['login', { path: '/login' }],
]);

export default pages;
```

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add feature name'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## Contact
For any questions or feedback, feel free to reach out:
- **LinkedIn**: www.linkedin.com/in/achal-bharadwaj
- **GitHub**:(https://github.com/Achal-Bharadwaj)

