# Chef's Culinary Experience Website

## Project Overview

This project involves the development of a website for a world-renowned chef offering a unique gastronomic experience. Users can explore exclusive menus, book culinary experiences at home, and interact with the chef. The platform supports multi-role functionality for both clients and the chef.

---

## Objectives

### Multi-Role Functionality

- **Users (Clients):**
  - Discover the chef's exclusive menus.
  - Register, log in, and book culinary experiences.
  
- **Chef (Administrator):**
  - Manage reservations (accept, decline, view statistics).
  - Update personal profile.

---

## Key Features

### **User Registration & Authentication**
- Secure sign-up and login functionality.
- Role-based redirection after authentication:
  - **User Role:** Redirect to menu and booking pages.
  - **Chef Role:** Redirect to an admin dashboard.

### **User Pages (Client)**
- **Explore Menus:** View menus and dishes curated by the chef.
- **Make Reservations:** Book culinary experiences by selecting a date, time, and guest count.
- **Reservation Management:** View booking history, modify, or cancel reservations.

### **Chef Dashboard**
- **Reservation Management:** Accept or reject requests based on availability.
- **Statistics Overview:**
  - Pending requests.
  - Approved reservations for today and tomorrow.
  - Next client and reservation details.
  - Total registered users.

### **Responsive Design**
- Fully responsive across mobile, tablet, and desktop devices.
- Modern, elegant design to reflect luxury and sophistication.
- Intuitive UI/UX for a seamless user experience.

---

## JavaScript Features

- **Form Validation:**
  - Regular expressions for validating inputs (email, phone, password).
- **Dynamic Menus:**
  - Add or remove dishes dynamically without page reloads.
- **Dynamic Modals:**
  - Display reservation details or confirmation dialogs via modals.
- **SweetAlert Integration:**
  - Elegant visual alerts for key actions (e.g., booking confirmation).

---

## Data Security

- **Password Hashing:** Secure hashing for all user passwords.
- **XSS Protection:** Input sanitization to prevent cross-site scripting attacks.
- **SQL Injection Prevention:** Use of prepared statements for database queries.
- **CSRF Protection (Bonus):** Tokens to secure sensitive actions like booking and profile updates.


