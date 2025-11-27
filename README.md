# hotel-booking-dashboard
Excel dashboard project analyzing hotel booking and cancellation trends.
 
It analyzes **booking trends, cancellations, room allocation, and guest types** to help hotel management understand performance and customer patterns.

---

## Dataset Overview

The project uses a cleaned hotel booking dataset stored in the `hotel_booking` sheet.

**Key columns:**

- `hotel` – Type of hotel (e.g., Resort Hotel, City Hotel)  
- `is_canceled` – 0 = not cancelled, 1 = cancelled  
- `arrival_date_year` – Year of arrival  
- `arrival_date_month` – Month of arrival  
- `adults`, `children`, `babies` – Number of guests  
- `country` – Country of the guest  
- `reserved_room_type` – Room type originally reserved  
- `assigned_room_type` – Room type actually assigned  
- `reservation_status` – Booking status (e.g., Check-Out, Canceled)  
- `reservation_status_date` – Date of final status  
- `room_status` – Desired / Un-Desired room  
- `guest_type` – e.g., Couples, Single, Family


---

## 🎯 Objectives

This dashboard aims to answer questions such as:

- How many bookings are **cancelled vs. not cancelled**?
- Which **hotel type** gets more bookings?
- Which **months and years** have the highest booking volume?
- Which **guest type** (Couples, Single, Family) is most frequent?
- How often is the **assigned room different from the reserved room**?

---

## 📊 Dashboard Features

The **Dashboard** sheet includes:

- **KPI Cards** for:
  - Total Bookings  
  - Total Cancellations   
  - Total Guests (Adults + Children + Babies)

> This makes the dashboard interactive: users can filter by time, hotel, or guest type.

---

## 🛠 Tools & Skills Used

- **Microsoft Excel**
  - Pivot Tables
  - Pivot Charts
  - Slicers / Filters
  - Basic data cleaning
- **Data Analysis Concepts**
  - Booking & cancellation analysis
  - Trend analysis (by year/month)
  - Customer segmentation (by guest type)
  - Room allocation comparison (reserved vs assigned)

---
