# Airbnb Clone Backend – User Stories

This document translates the use case diagram interactions into actionable **user stories**.  
Each story describes what a user (actor) wants to achieve and why, guiding developers in building user-focused features.

---

## Actors
- **Guest** – A user who books and reviews properties.
- **Host** – A user who lists and manages properties.
- **Admin** – A superuser who oversees all activities.
- **Payment Gateway** – External service for payment processing.
- **Notification System** – External service for sending alerts and confirmations.

---

## User Stories

### Guest User Stories
1. **User Registration**
   > As a guest, I want to create an account so that I can book and manage my property reservations.

2. **Search and Booking**
   > As a guest, I want to search for available properties by location, price, and amenities so that I can find a suitable place to stay.

3. **Payment**
   > As a guest, I want to make secure payments for my bookings so that I can confirm my reservation without issues.

4. **Booking Management**
   > As a guest, I want to view and cancel my bookings so that I can manage my travel plans easily.

5. **Review Submission**
   > As a guest, I want to leave reviews and ratings for properties I’ve stayed in so that I can share my experience and help other users.

---

### Host User Stories
6. **Property Listing**
   > As a host, I want to add new properties with descriptions, photos, and prices so that guests can book them.

7. **Property Management**
   > As a host, I want to edit or delete my property listings so that I can keep my listings accurate and up to date.

8. **Booking Oversight**
   > As a host, I want to view and manage my property bookings so that I can keep track of my reservations and guests.

9. **Review Response**
   > As a host, I want to respond to guest reviews so that I can maintain transparency and improve my reputation.

---

### Admin User Stories
10. **System Oversight**
    > As an admin, I want to monitor all users, bookings, and payments so that I can ensure the platform runs smoothly.

11. **User Management**
    > As an admin, I want to suspend or remove users who violate the platform’s policies so that I can maintain a safe environment.

12. **Report Generation**
    > As an admin, I want to generate system and financial reports so that I can analyze platform performance.

---

### Payment Gateway Stories
13. **Payment Processing**
    > As a payment gateway, I want to process guest payments securely so that hosts receive funds once a booking is completed.

14. **Refund Handling**
    > As a payment gateway, I want to handle cancellations and refunds so that guests receive their money back when eligible.

---

### Notification System Stories
15. **Booking Notifications**
    > As a notification system, I want to send confirmation emails and alerts to users so that they stay updated on their booking status.

16. **Payment Notifications**
    > As a notification system, I want to notify users of successful or failed payments so that they have clarity on their transactions.

---

## Summary
These user stories capture the main system interactions between the key actors (Guest, Host, Admin, and External Services) and the backend.  
They serve as a foundation for defining **API endpoints**, **database operations**, and **business logic** in subsequent development stages.