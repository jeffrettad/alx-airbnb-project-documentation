# Task 1: Use Case Diagram of the Airbnb Clone Backend

## 🎯 Objective
The purpose of this diagram is to illustrate how different **actors** (users, hosts, admins, and external services) interact with the **Airbnb Clone backend system**.  
It provides a **high-level overview** of system functionalities from the user’s perspective.

---

## 👥 Actors
- **Guest**: Can register, log in, search for properties, book properties, make payments, and leave reviews.  
- **Host**: Can register, log in, create/edit/delete property listings, manage bookings, and respond to reviews.  
- **Admin**: Manages users, properties, bookings, and payments.  
- **Payment Gateway (Stripe/PayPal)**: Handles secure transactions between guests and hosts.  
- **Email/Notification Service (SendGrid/Mailgun)**: Sends booking confirmations, cancellations, and payment notifications.  

---

## 🗂️ Use Cases

### Guest
- Register / Login  
- Search and Filter Properties  
- View Property Details  
- Book a Property  
- Make Payment  
- Cancel Booking  
- Leave Review  

### Host
- Register / Login  
- Add Property Listing  
- Edit / Delete Property Listing  
- View & Manage Bookings  
- Respond to Reviews  

### Admin
- Manage Users  
- Manage Listings  
- Manage Bookings  
- Manage Payments  

### External Services
- **Payment Gateway**: Process guest payments and host payouts.  
- **Email Service**: Send notifications for bookings and payments.  

---

## 📊 Use Case Diagram
Below is the **use case diagram** representation of the Airbnb Clone backend:

![Use Case Diagram](/use-case.png)

---

## ✅ Deliverables
- `use-case-diagram/use-case.png` → Visual diagram of actors and system interactions.  
- `use-case-diagram/README.md` → This documentation.  
