# Automatic Currency Withdrawal & Stock Update System


## Project Overview

Automatic Currency Withdrawal & Stock Update System is a cloud-based automation solution designed to manage currency distribution efficiently using Google Forms, Google Sheets, and Google Apps Script.

It eliminates manual errors, prevents over-withdrawal, and ensures real-time stock visibility. Users can request currency denominations through a dynamic form, and the system automatically updates inventory, logs transactions, and sends confirmations.

This system is suitable for schools, offices, hospitals, and institutions that require controlled and transparent cash handling.

---

## Technologies Used

* Google Forms – User interface for withdrawal requests
* Google Sheets – Real-time inventory database
* Google Apps Script – Automation and backend logic
* Gmail API (via Apps Script) – Automated email notifications
* Cloud-Based Workflow – No hardware dependency

---

## Key Features

### Real-Time Inventory Management

* Displays only available denominations
* Updates stock instantly after each transaction

### Full Automation

* No manual intervention required
* Automatic deduction of requested currency

### Instant Confirmation

* Sends email with:

  * Requested denominations
  * Quantity
  * Timestamp

### Audit Trail

* Logs every transaction with user details
* Helps in monitoring and analysis

### Over-Withdrawal Prevention

* Users cannot request unavailable denominations

### Dynamic Form Updates

* Form adapts based on live stock
* Shows "Available: X" for each denomination

---

## Project Structure


Automatic-Currency-System/
│
├── Google Form (UI for requests)
├── Google Sheet (Inventory + Logs)
├── Apps Script (Automation logic)

## How It Works

### Step-by-Step Flow

1. Stock Initialization

   * Admin sets currency stock in Google Sheet

2. Dynamic Form Display

   * Form shows only available denominations

3. User Request

   * User selects denominations and submits form

4. Automation Trigger

   * Apps Script:

     * Checks availability
     * Deducts stock
     * Logs transaction

5. Email Confirmation

   * User receives transaction details instantly

6. Form Refresh

   * Updates available denominations for next user

---

## Example Workflow

* User selects denominations
* System verifies availability
* Stock is updated automatically
* Confirmation email is sent
* Data is logged for tracking
<img width="1920" height="952" alt="image" src="https://github.com/user-attachments/assets/63c89ca5-625c-4760-9cae-3bab200681a4" />
<img width="1911" height="942" alt="image" src="https://github.com/user-attachments/assets/7bea4323-8b59-4a14-9ce8-fd1806e7c1ce" />
<img width="1898" height="1001" alt="image" src="https://github.com/user-attachments/assets/942e4ff9-ff53-40e2-8f55-4a322720fbc1" />

## Real-World Applications

* Schools – Manage student cash distribution
* Offices – Handle internal fund allocation
* Hospitals – Track petty cash usage
* Government Institutions – Transparent fund handling

---

## Future Enhancements

* Role-Based Access Control (Admin / User / Supervisor)
* Advanced Analytics Dashboard (charts and reports)
* Database Integration (MySQL or SQLite)
* Cloud Backup and Multi-Device Sync
* Secure Authentication (encrypted login)
* AI-Based Smart Limits (adaptive usage control)
* Mobile App Integration

---

## Achievements

* Selected for College-Level Project Expo at SR University
* Designed as a patent-ready system

---

## Novelty

This system introduces a unique combination of cloud tools to automate:

* Real-time stock updates
* Dynamic form generation
* Automated communication

Unlike traditional systems, it is:

* Lightweight
* Cost-effective
* Fully cloud-based
* No hardware dependency
