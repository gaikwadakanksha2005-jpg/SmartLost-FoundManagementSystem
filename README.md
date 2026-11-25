
# 🎓 Smart Lost & Found Management System

## 📌 Project Overview

The **Smart Lost & Found Management System** is a web-based application designed to help students report, search, and recover lost belongings within a college campus.

Students often lose personal belongings such as identity cards, books, wallets, keys, bags, and electronic devices. Managing lost and found items manually can lead to delays, confusion, and difficulties in identifying the rightful owners.

This project provides a centralized platform where students can report missing items, register found items, search existing reports, and submit claims to recover their belongings. The system also maintains an updated Missing Item Checklist and provides notifications about important item updates.

The system includes an administrator-led verification process to ensure that items are returned only to their rightful owners.

## 🎯 Problem Statement

The existing manual process of managing lost and found items in colleges is often time-consuming and unorganized. Students may find it difficult to locate their lost belongings or identify whether someone has submitted a found item.

There is a need for a centralized web-based system that simplifies the reporting, searching, matching, claiming, and tracking of lost and found items within the college community.

## 🎯 Project Objectives

- To develop a web-based platform for managing lost and found items.
- To allow students to report missing items and register found items.
- To provide search and filtering facilities for reported items.
- To identify possible matches based on item name, category, description, location, and date.
- To maintain an updated Missing Item Checklist.
- To manage item statuses through Missing, Found, Claimed, and Returned stages.
- To provide a claim submission and administrator-led verification process.
- To allow administrators to manage users, reports, claims, and item statuses.
- To generate QR codes for quick access to item records.
- To provide notifications about important updates related to reported items.

## ✨ Key Features

- **User Registration & Login:** Secure login and registration for students and administrators.
- **Lost Item Reporting:** Students can report missing belongings with relevant details.
- **Found Item Registration:** Found items can be registered in the system.
- **Search & Filtering:** Search items using name, category, location, and date.
- **Possible Item Matching:** Identify possible matches between lost and found reports.
- **Claim & Verification:** Students can submit claims, which are reviewed by the administrator.
- **Missing Item Checklist:** Maintain updated records of reported items and their current status.
- **Notifications:** Display important updates about found items and claim requests.
- **QR Code Generation:** Generate QR codes linked to individual item records.
- **Item Status Tracking:** Track items from reporting to final return.

## 🛠️ Technology Stack

### Frontend
- HTML5
- CSS3
- Bootstrap
- JavaScript

### Backend
- Python
- Flask Framework

### Database
- MySQL

### Tools & Development Environment
- Visual Studio Code
- Git & GitHub
- Figma (UI Design)

## 🧩 Functional Modules

The system consists of seven main functional modules.

### 1. User Authentication & Role Management
- Student and administrator registration and login.
- Role-based access control.
- Management of student details such as name, class, division, roll number, and contact information.
- Administrator facilities to manage users and system activities.

### 2. Lost & Found Item Management
- Submit lost and found item reports.
- Add item name, category, description, date, time, location, and identification marks.
- Upload item images (optional).
- Maintain an updated Missing Item Checklist.
- Display item information and current status.

### 3. Claim & Verification Management
- Allow students to submit claims for lost belongings.
- Collect additional identifying details or proof.
- Enable administrators to review, approve, or reject claims.
- Verify the rightful owner before handing over an item.
- Record the return date and remarks.

### 4. Notification Management
- Display notifications related to found items.
- Notify users about claim approval or rejection.
- Provide updates about returned items.
- Maintain notification records for users.

### 5. Search & Matching Management
- Search items using item name, category, location, and date.
- Compare lost and found item details.
- Display possible matches to users.
- Support easier identification of lost belongings.

### 6. QR Code Identification
- Generate a unique QR code for each item record.
- Link the QR code to the relevant item information page.
- Display item details and current status when scanned.
- Provide quick access to item records.

### 7. Item Status Tracking
- Track the complete lifecycle of reported items.
- Maintain item statuses such as Missing, Found, Claimed, and Returned.
- Record status updates, dates, and remarks.
- Provide a verification checklist before returning an item.

## 🔄 System Workflow

1. A student registers and logs into the system.
2. The student reports a lost item or registers a found item.
3. The system stores the submitted information in the database.
4. Students can search and view available item reports.
5. The system identifies and displays possible matches.
6. A student submits a claim with additional identification details.
7. The administrator verifies the claim.
8. After successful verification and handover, the administrator updates the item status to Returned.
9. The system maintains updated records and displays relevant notifications.

## 📋 Missing Item Checklist

The system maintains a checklist to help administrators monitor lost and found items.

| Sr. No. | Field Description |
|---|---|
| 1 | Item Name |
| 2 | Item Description |
| 3 | Date Reported |
| 4 | Location |
| 5 | Student Name |
| 6 | Current Status |
| 7 | Date Found / Returned |
| 8 | Remarks |

## 🔐 Security & Verification

- Role-based access for students and administrators.
- Authentication for accessing system features.
- Administrator verification before returning an item.
- Additional identification details during claim submission.
- QR code scanning does not establish ownership.
- Multiple claims for the same item are reviewed by the administrator.

## 📦 Expected Outcomes

The Smart Lost & Found Management System aims to provide an organized and convenient way to manage lost and found belongings within the college campus.

The expected outcomes include:

- Reduced manual effort in managing lost and found items.
- Faster searching and identification of possible item matches.
- Centralized and updated item records.
- Improved communication through notifications.
- Proper claim verification before returning belongings.
- Better tracking of item status from Missing to Returned.
- Quick access to item information through QR codes.

## 🚀 Future Scope

- Email and SMS notifications.
- Advanced item matching using intelligent algorithms.
- Mobile-friendly application.
- Improved analytics and reporting for administrators.
- Integration with college management systems.

## 👩‍💻 Project Team

**Team Name:** CodeFusion

**Team Members:**
- Akanksha Gaikwad
- Vaishnavi

## 🎓 Academic Project

Developed as part of the **Master of Computer Applications (MCA)** academic curriculum.

---

⭐ *Smart Lost & Found Management System – Helping students find what they have lost!*
