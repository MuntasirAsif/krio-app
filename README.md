# Krio - App Based Job Marketplace

Krio is a mobile-first job marketplace platform that connects **job seekers** with **clients** who need services for short-term tasks or projects.

The platform allows job seekers to create service cards and bid on jobs, while clients can post jobs and hire nearby workers.

---

# Features

## Authentication System

### Sign Up

Users can register as:

- Job Seeker
- Client

Fields:

- Name
- Email
- Phone Number
- Password
- Google Sign In (Optional)

### Password Validation Rules

Password must contain:

- Minimum **8 characters**
- At least **1 lowercase letter**
- At least **1 uppercase letter**
- At least **1 digit**
- At least **1 special character**
- Confirm password must match

### Login

Users login using:

- Username or Email
- Password

Unauthorized users cannot access protected pages.

---

# User Roles

## Job Seeker

Job seekers can create profiles, publish service cards, browse jobs, and submit bids.

### Profile & KYC Verification

Profile Fields:

- Name (as NID)
- Phone Number
- Current Address (Google Map text field)
- Permanent Address (Google Map text field)
- NID Number
- NID Photo
- Student ID (if student)
- Passport (if foreigner)
- User Photo (Camera verification using Google ML Kit)

Some verification steps are **optional but recommended**.

---

# Profile Completion

The system shows:

- Profile completion percentage
- Profile verification status

Users must complete verification to unlock full features.

---

# Service Card Creation (Job Seeker)

Job seekers can create a **service card** to advertise their skills.

Fields:

- Card Title
- Job Category
- Description (HTML text)
- Cover Photo
- Tags
- Job Opening Time
- Job Closing Time
- Hourly Pricing
- Workload Level:
  - Low
  - Medium
  - High

Cards can be saved as:

- Draft
- Published
- Resume

Users cannot delete cards after publishing.

More than **3 cards require a premium subscription**.

---

# Job Discovery

Job seekers can:

- View nearby jobs
- Search by keyword
- Filter by:
  - Category
  - Map radius
  - Location

---

# Bidding System

Job seekers can send bids with:

- Proposed price
- Description
- Interest button

Clients review bids and select candidates.

---

# Work History

Job seekers can track:

- Pending Offers
- Accepted Offers
- Rejected Offers
- Not Responded Offers

---

# Task Manager

Tasks are categorized as:

- Running Tasks
- Pending Tasks
- Previous Tasks

---

# Experience Hub

Users can upload certificates.

Multiple certificates require **premium access**.

---

# Profile Statistics

Users can see:

- Profile visitors
- Total bids
- Pending tasks
- Completed tasks

---

# Client (Customer)

Clients can create jobs and hire job seekers.

---

# Job Creation

Clients can create job posts with:

- Job Title
- Job Category
- Description
- Cover Photo (optional)
- Tags (optional)
- Job Time
- Location (required)
- Budget

---

# Hiring Workflow

1. Client posts a job
2. Job seekers send bids
3. Client reviews bids
4. Client sends offer
5. Job seeker accepts offer
6. Client completes payment
7. Job starts

Rules:

- Job cannot be cancelled **after 5 minutes of payment**
- If job seeker marks task complete:
  - Client confirms completion
  - If no response within **15 minutes**, job auto completes

---

# Rating & Reviews

After job completion:

- Clients can rate job seekers
- Reviews appear on profiles

---

# Job Manager

Clients can manage:

- Running Jobs
- Pending Jobs
- Completed Jobs
- Cancelled Jobs

---

# Search & Filters

Users can search by:

- Job keyword
- Category
- Map radius
- Area

---

# Notifications

Users receive notifications for:

- Job alerts
- Campaign updates
- Offers
- System messages

---

# Settings

Users can control:

- Show phone number
- Show address
- Dark mode / Light mode
- Language
- Feedback
- Contact support
- Delete account
- Logout

---

# Payment System

Clients must pay before a job starts.

Payment system supports:

- Job payment
- Extra payment

Clients can view payment history.

---

# Technology Stack

Frontend

- Flutter / React Native (App)
- HTML / CSS / JavaScript (Web panel)

Backend

- Node.js / Express
or
- Django / Laravel

Database

- MongoDB / MySQL

APIs

- Google Maps API
- Google ML Kit
- Authentication API

---

# Security Features

- Strong password validation
- Duplicate email protection
- Secure authentication
- KYC verification
- Session protection
- Restricted access control

---

# Future Improvements

- Real payment gateway integration
- AI job recommendation
- Real-time chat
- Push notifications
- Advanced analytics

---

# Author

Krio Project  
App-Based Job Marketplace Platform
