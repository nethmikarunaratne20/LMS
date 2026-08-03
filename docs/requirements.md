# Library Management System - System Requirement Specification

## 1. Project Overview
ALexandria is a web-based application designed to help librarians manage books, members, borrowing, returns, fines, and notifications.


## 2. Problem Statement
The library currently manages borrowing manually using paper records and spreadsheets, making it difficult to track overdue books and member activity.

## 3. Actors
Librarian (Admin)
Member

## 4. Functional Requirements
- Authentication
    - Login

- Book Management
    - Add Book
    - Edit Book
    - Delete Book
    - Search Book

- Member Management
    - Register Member
    - Edit Member

- Loan Management
    - Borrow Book
    - Return Book

- Notification Management
    - Send Reminder Emails

- Reports
    - View Reports

## 5. Non-functional Requirements
- Secure authentication
- Responsive UI
- Fast search
- Daily backups (future)
- Email notifications
- Data validation

## 6. Business Rules
- Fine is Rs.10 per day.
- Each book has only one copy.
- Borrow period is 14 days.
- Only librarians may add/delete books.
- A member cannot borrow more than 3 books within a week.

