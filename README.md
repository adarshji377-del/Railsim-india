1. Introduction & Project Overview
The Railway Passenger Berth Availability And Waitlist Pnr Status Simulator is an interactive frontend
web application developed as part of the CSE326 project by team members Shery Samrat (12627884),
Adarsh Gupta (12611678), and Paidakula Lokeshwar (12608640).
Train travelers checking train seat availability across classes (1st AC, 2nd AC, 3rd AC, Sleeper Class)
often struggle to understand railway reservation terms (Confirmed, RAC, WL Waitlist, Tatkal quota) and
predict whether waitlisted tickets will confirm before travel. This train simulator models seat availability and
PNR lookups, providing an intuitive, interactive frontend solution that addresses this need without relying
on backend services.
Key Functional Features Implemented:
Train Search Form: Allows travelers to select Origin Station, Destination Station, Travel Date,
and Reservation Quota (General, Tatkal, Senior Citizen).
Class-Wise Seat Availability Cards: Displays status across 1A, 2A, 3A, and SL classes with
color-coded indicators (Available 42 Seats in Green, RAC 14 in Yellow, WL 28 in Red).
Simulated 10-Digit PNR Status Tracker: Accepts a 10-digit PNR number and displays a
comparison table of Passenger Booking Status vs. Current Status.
Waitlist Confirmation Probability Meter: Displays High / Medium / Low confirmation chances
using HTML5 progress meters based on historical cancellation trends.
This documentation covers the full source code implementation across all three core web pages
(index.html, book.html, and status.html). To make the code easy to explain during the viva
examination, each module is first presented in divided logical parts followed by its complete source code
and rendered output preview
