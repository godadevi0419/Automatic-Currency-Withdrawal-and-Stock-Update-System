Automatic Currency Withdrawal & Stock Update System

Project Overview
Automatic Currency Withdrawal & Stock Update System is a cloud-based automation solution designed to manage currency distribution efficiently using Google Forms, Google Sheets, and Apps Script.
It eliminates manual errors, prevents over-withdrawal, and ensures real-time stock visibility. Users can request currency denominations through a dynamic form, and the system automatically updates inventory, logs transactions, and sends confirmations — like a silent accountant working 24/7 🧾⚙️
This system is ideal for schools, offices, hospitals, and institutions that require controlled and transparent cash handling.
Technologies Used
Google Forms – User interface for withdrawal requests
Google Sheets – Real-time inventory database
Google Apps Script – Automation and backend logic
Gmail API (via Apps Script) – Automated email notifications
Cloud-Based Workflow – No hardware dependency
 Key Features
>>Real-Time Inventory Management
>>Displays only available denominations
>>Updates stock instantly after each transaction
>>Full Automation
>>No manual intervention required
>>Automatic deduction of requested currency
>>Instant Confirmation
Sends email with:
Requested denominations
Quantity
Timestamp
Audit Trail
Logs every transaction with user details
Helps in monitoring and analysis
Over-Withdrawal Prevention
Users cannot request unavailable denominations
 Dynamic Form Updates
Form adapts based on live stock
Shows “Available: X” for each denomination
📁 Project Structure
Automatic-Currency-System/
│
├── Google Form (UI for requests)
├── Google Sheet (Inventory + Logs)
├── Apps Script (Automation logic)
├── README.md
 How It Works
Step-by-Step Flow 
Stock Initialization
Admin sets currency stock in Google Sheet
Dynamic Form Display
Form shows only available denominations
User Request
User selects denominations and submits form
Automation Trigger
Apps Script:
Checks availability
Deducts stock
Logs transaction
Email Confirmation
User receives transaction details instantly
Form Refresh 
Updates available denominations for next user
 Example Workflow
<img width="949" height="501" alt="image" src="https://github.com/user-attachments/assets/4cc05d16-0b1c-43f5-9b75-1fd74f889555" />
<img width="1920" height="952" alt="image" src="https://github.com/user-attachments/assets/5e81b65e-4779-4a54-8ffc-65727893e449" />
<img width="1911" height="942" alt="image" src="https://github.com/user-attachments/assets/7a3b457d-9f35-4c35-a291-ae3b84c38ad7" />

Imagine a vending machine… but for currency logic 🏧✨

You ask → system checks → system gives → system updates → system remembers

No confusion. No manual tracking. Just smooth flow.

 Real-World Applications
Schools – Manage student cash distribution
Offices – Handle internal fund allocation
Hospitals – Track petty cash usage
Government Institutions – Transparent fund handling
Future Enhancements
>>Role-Based Access Control (Admin / User / Supervisor)
>> Advanced Analytics Dashboard (charts & reports)
>> Database Integration (MySQL / SQLite)
>> Cloud Backup & Multi-Device Sync
>> Secure Authentication (encrypted login)
>> AI-Based Smart Limits (adaptive usage control)
>> Mobile App Integration
🏆 Achievements
Selected for College-Level Project Expo at SR University.
Designed as a patent-ready system with real-world applicability
Novelty

This system introduces a unique combination of cloud tools to automate:

Real-time stock updates
Dynamic form generation
Automated communication

Unlike traditional ATM or ERP systems, it is:
 Lightweight
Cost-effective
Fully cloud-based
Zero hardware dependency
