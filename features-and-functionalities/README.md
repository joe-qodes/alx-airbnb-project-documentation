# Airbnb Clone – Backend Features & Functionalities

This document outlines the **core backend features** required for the Airbnb Clone project. It is supported by a system diagram (see `features-and-functionalities.png`) created using [Draw.io](https://app.diagrams.net/).

---

## 🔑 Key Features

### 1. User Management & Authentication
- User registration (guest, host).
- Secure login with hashed passwords.
- Session/token-based authentication (e.g., JWT).
- User profile management (name, email, phone, role).
- Role-based access control (guest vs. host vs. admin).

### 2. Property Management (Host)
- Create, update, and delete property listings.
- Upload and manage property images.
- Define property details (location, description, amenities, nightly price).
- Availability management (set available/unavailable dates).
- View bookings for owned properties.

### 3. Booking System (Guest)
- Search properties by location, date, and price.
- View property details.
- Make a booking request.
- Modify or cancel a booking (depending on status).
- Booking statuses: **pending, confirmed, cancelled**.
- Prevent double booking for the same property.

### 4. Payment Processing
- Link payment to bookings.
- Payment methods: credit card, PayPal, etc.
- Store payment details securely.
- Track transaction history.
- Refund management (if booking is cancelled).

### 5. Reviews & Ratings
- Guests can leave reviews for properties.
- Ratings system (1–5 stars).
- Hosts can reply to reviews.
- Reviews visible on property details.

### 6. Messaging System
- Direct messages between guest and host.
- Store message history.
- Support notifications for new messages.

### 7. Admin Dashboard (Optional / Stretch Feature)
- Manage users, properties, and bookings.
- Resolve disputes.
- View system analytics.

---

## 📊 Features & Functionalities Diagram

The following diagram illustrates the **high-level interactions** between system components:

![Features and Functionalities Diagram](features-and-functionalities.png)

---

## 📂 Repository Structure

