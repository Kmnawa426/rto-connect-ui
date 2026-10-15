# RTO Connect - Modern UI Template with Client-Side JavaScript

A modern, responsive, multi-page HTML/CSS/JS interface for an RTO driving licence and vehicle portal. Includes client-side interactions, user session simulation via `localStorage`, animated dropdowns, mobile navigation, toast notifications, and client-side authentication validation.

## Features & JavaScript Functionalities
- **User Profile Dropdown (`js/app.js`)**: Interactive dropdown menu showing avatar, active user details, quick links (Applications, Training, Fines, Notifications), and Sign Out action. Closes on outside click or Escape key.
- **Client-Side Auth & Validation (`js/auth.js`)**:
  - `login.html`: Email/phone and password validation, simulated sign-in with active session storage, password show/hide toggle, and "Forgot password" modal simulation.
  - `register.html`: Validation for full name, email format, 10-digit mobile number, and password rules. Stores user credentials in `localStorage` and logs in automatically.
- **Session State Synchronization**: Dynamically updates the header across all 12 pages based on whether the user is logged in or guest.
- **Mobile Responsive Navigation**: Touch-friendly hamburger menu for smartphones and tablets.
- **Interactive UI Feedback**: Floating toast notification banners for actions (payments, logins, form submissions).
- **Interactive Simulations**: Instant challan payment simulation on `fines.html`, simulated licence application submissions on `apply.html` and `apply-licence.html`.

## Pages Included
- `index.html` - Overview Dashboard
- `services.html` - Licence & Permit Services
- `apply.html` - General Service Application
- `apply-licence.html` - Driving Licence Application
- `applications.html` - Application Tracking & Status
- `training.html` - Driving School Training & Progress
- `driving-test.html` - Driving Test Schedule & Checklist
- `fines.html` - Fines & e-Challan Management (with interactive payment simulation)
- `notifications.html` - System & Application Alerts
- `login.html` - Sign In with client-side validation
- `register.html` - Account Creation with field validation
- `school-register.html` - Partner Driving School Onboarding

## How to Run
Simply open `index.html` (or any `.html` page) in any modern web browser. No server, Node.js, or backend setup is required.
