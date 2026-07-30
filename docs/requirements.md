# Library Management System - SRS

## 1. Project Overview
This Library Management System is a web-based application designed to help librarians manage books, members, borrowing, returns, fines, and notifications.


## 2. Problem Statement
The library currently manages borrowing manually using paper records and spreadsheets, making it difficult to track overdue books and member activity.

## 3. Actors
Librarian (Admin)
Member

## 4. Functional Requirements
- Admin can 
    - Login
    - Add/delete/edit books
    - Add/remove authors
    - Register members
    - Record borrowing/returning of books
    - Send notifying emails
    - Calculate fines
    - View reports 

- Members can
    - Borrow/return books
    - Receive emails

## 5. Non-functional Requirements
- Secure authentication
- Responsive UI
- Fast search
- Daily backups (future)
- Email notifications
- Data validation

## 6. Business Rules
- Fine is Rs.10 per day.
- Borrow period is 14 days.
- Only librarians may add/delete books.
- A member cannot borrow more than 3 books within a week.

