# Task 4: Flowchart for Airbnb Clone Backend

## 🎯 Objective
The goal of this task is to represent one of the key backend processes of the Airbnb Clone as a **flowchart**.  
This diagram provides a step-by-step visualization of how data flows and decisions are made in the system.

---

## 🏷️ Selected Process: Property Booking
We selected the **Property Booking process** because it involves multiple interactions between the **Guest**, **Host**, **Backend system**, and **Payment service**.

---

## 🗂️ Flowchart Description

1. **Guest logs in** → Ensures only authenticated users can book.  
2. **Search for property** → Query the database for available listings.  
3. **Select property & check availability** → The system verifies if the chosen dates are free.  
4. **Confirm booking request** → Guest submits booking.  
5. **Process payment** → Payment gateway (e.g., Stripe) handles transaction securely.  
6. **Payment success?**
   - ✅ Yes → Booking confirmed, system notifies Host & Guest.  
   - ❌ No → Display error and allow Guest to retry.  
7. **Update database** → Save booking details and availability changes.  
8. **Send notifications** → Email/SMS confirmation to Guest and Host.

---

## 📌 Deliverables
- `flowcharts/booking-flowchart.png` → Flowchart exported from Draw.io  
- `flowcharts/README.md` → This documentation
