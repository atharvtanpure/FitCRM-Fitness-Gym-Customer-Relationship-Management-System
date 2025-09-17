# FitCRM: A Salesforce-based Fitness & Gym Customer Relationship Management System

## 📌 Project Overview
FitCRM is a custom-built **Fitness & Gym CRM solution** developed on the Salesforce platform.  
It helps gyms and fitness centers manage **memberships, trainers, attendance, referrals, and renewals** efficiently.  
The project leverages Salesforce **Sales Cloud, Flow Automation, and Dashboards** to deliver a seamless experience for both gym admins and members.

---

## 🎯 Features
- **Lead Management**
  - Capture and track new inquiries (Leads).
  - Convert interested leads into members (Contacts).

- **Membership Management**
  - Automate membership **renewal reminders** via email/SMS.
  - Track expired vs active memberships.

- **Attendance Tracking**
  - Log daily member attendance.
  - Monitor trainer performance based on client check-ins.

- **Referral & Loyalty Program**
  - Members earn loyalty rewards when they refer new members.
  - Track referral source for lead generation.

- **Dashboards & Reports**
  - Active vs Inactive members.
  - Monthly revenue from memberships.
  - Trainer performance overview.
  - Referral impact on new memberships.

---

## 🏗️ System Design

### 📌 Objects Used
- **Lead** → New inquiries about gym membership.
- **Contact (Member)** → Active gym members.
- **Opportunity** → Membership purchase/renewal deals.
- **Custom Object: Attendance** → Tracks daily check-ins.
- **Custom Object: Referral** → Tracks referral details and rewards.
- **Trainer (Custom Object)** → Stores trainer details and performance metrics.

### 📌 Relationships
- One **Member (Contact)** → Many **Attendance Records**.
- One **Member** → Many **Referrals**.
- One **Trainer** → Many **Members** assigned.

---

## ⚡ Automation
- **Flow/Process Builder**
  - Auto-send renewal reminder **7 days before expiry**.
  - Award loyalty points when a referral converts into a new member.
  - Assign new members to trainers automatically.

- **Validation Rules**
  - Prevent duplicate referrals from the same member.
  - Ensure membership cannot be expired without a renewal option.

---

## 📊 Dashboards
- **Membership Dashboard**
  - Active vs Expired memberships.
  - Monthly revenue trend.

- **Trainer Dashboard**
  - Attendance count of assigned members.
  - Top-performing trainers.

- **Referral Dashboard**
  - Number of referrals converted.
  - Loyalty rewards distribution.

---

## 🚀 Technologies Used
- **Salesforce Sales Cloud**
- **Salesforce Flow / Process Builder**
- **Custom Objects & Relationships**
- **Reports & Dashboards**
- **Email/SMS Notifications (Integration with Salesforce Messaging)**

---

## 🎯 Benefits
- Improves **member retention** through automated reminders.
- Enhances **trainer accountability** with performance tracking.
- Boosts **gym revenue** with referral-based loyalty rewards.
- Provides gym owners with **real-time insights** via dashboards.

---

## 📌 Future Enhancements
- Mobile App Integration for members to check attendance & rewards.
- Integration with **IoT gym equipment** for auto-attendance.
- AI-based fitness recommendation system using Salesforce Einstein.

---

## 👤 Author
**Atharv Tanpure**  
 
