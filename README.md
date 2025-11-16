**Investor Management Panel (Web-Based)**

This project is a web-based management panel designed for internal use only. Users do not interact with the system directly; all data is entered manually by admins through the panel. The goal is to simplify managing investor information, tracking contracts, monitoring payouts, and sending reminders.

**Features**
1. Investor Information Management
The system stores and manages detailed investor profiles, including:
Full name
National ID
Bank account number
Phone number
Investment status (investor, introducer, or both)
Admins can:
Add new investors
Edit existing profiles
Delete investor records
Add or update introducers later if needed

2. Contract and Investment Details
Each investor can have contract details stored with:
Contract date
Contract type
Investment percentage (1%–10%)
Assigned introducer (optional)
The system calculates returns based on the rule:
For every 100,000,000 (100M) invested → 5,000,000 (5M) profit
The calculated profit is shown next to each investor’s record.

3. Profit Payment Tracking
The panel allows admins to mark payouts as “paid.”
Once marked, a countdown starts toward the next payout date.
Admins can view how many days remain until the next payout cycle.

4. Automated Notifications
The system sends reminders:
One day before the payout date, an SMS notification is automatically sent indicating that the investor’s payout is due tomorrow.
Support for:
SMS notifications
Social media notifications

5. Introducer Commission History
The system records:
Commission history
Introducers involved
Percentage belonging to each introducer
This ensures transparent tracking of referral-based earnings.

6. Search & Filtering
Admins can search data using:
Date
Name
Bank account number
National ID
Investment amount

7. Data Storage
All data is:
Stored securely
Saved in a database
Accessible only through the admin panel at the domain address

8. Print & Export
Admins can:
View payout histories
Print payout dates and investor details for offline records
