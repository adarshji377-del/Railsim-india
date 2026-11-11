# Railway Passenger Berth Availability And Waitlist PNR Status Simulator

**Course Code:** CSE326 (First Year B.Tech Web Development Project)

## Team Members
* **Shery Samrat** — Registration No: `12627884`
* **Adarsh Gupta** — Registration No: `12611678`
* **Paidakula Lokeshwar** — Registration No: `12608640`

## Project Overview
Train travelers checking seat availability across classes (**1st AC, 2nd AC, 3rd AC, Sleeper Class**) often struggle to understand railway reservation terms (**Confirmed, RAC, WL Waitlist, Tatkal Quota**) and predict whether waitlisted tickets will confirm before travel. This project provides an interactive frontend simulator built using HTML5 and CSS3.

## Key Features & Modules
1. **`index.html` (Homepage Module):** Welcoming portal and simple guide explaining Confirmed (CNF), RAC, Waitlist (WL), and Quota systems.
2. **`book.html` (Booking & Berth Availability Module):**
   * Train search form with Origin Station, Destination Station, Travel Date, and Quota (General, Tatkal, Senior Citizen).
   * Class-wise seat availability cards (`1A`, `2A`, `3A`, `SL`) displaying color-coded statuses (**Available 42 Seats** in Green, **RAC 14** in Yellow, **WL 28** in Red).
3. **`status.html` (PNR Status Tracking Module):**
   * Simulated PNR status tracker taking a 10-digit PNR number and displaying **Passenger Booking Status vs. Current Status**.
   * **Waitlist Confirmation Probability Meter** (`High / Medium / Low`) based on historical cancellation trends.