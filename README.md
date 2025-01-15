# Hotel Management System 🏨

This **Hotel Management System** project is a console-based application written in C++ that allows hotels to manage customer information, room bookings, and food orders efficiently. It provides functionalities like room allocation, customer details management, billing, and restaurant services.

---

## Features 🚀

1. **Room Booking:**
   - Allocate rooms based on availability.
   - Categorize rooms into **Deluxe**, **Executive**, and **Presidential** classes with varying costs.

2. **Customer Information Management:**
   - Add, view, and edit customer details such as name, address, phone number, and duration of stay.

3. **Restaurant Services:**
   - Customers can order breakfast, lunch, and dinner, with charges added to their room bills.

4. **Billing System:**
   - Automatically calculates total charges for the stay and food services.

5. **Room Status Tracking:**
   - View a list of all allocated rooms with associated customer details.

6. **Customer Check-Out:**
   - Clear a room when a customer checks out and finalize their bill.

---

## Project Structure 📁

- **Class HOTEL**:
  - Handles all operations, including room booking, customer management, and food ordering.
  - Stores customer details and processes billing.

- **Main Menu**:
  - Provides a user interface to access all features.

---

## Room Categories 🛏️

| Room Number Range | Room Type      | Cost per Day |
|-------------------|----------------|--------------|
| 1–50             | Deluxe         | ₹5000        |
| 51–80            | Executive      | ₹7500        |
| 81–100           | Presidential   | ₹10000       |

---