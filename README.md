# DBMS Overview Reference

## Summary
A Database Management System (DBMS) is software that allows users to create, maintain, and control access to databases.

**Primary Goal:**  
Make storing and retrieving information both convenient and efficient.

## Examples of DBMS
- **Enterprise:** Oracle, DB2, SQL-Server
- **Open Source:** MySQL, PostgreSQL, Firebird, SQLite
- **Desktop/Local:** Microsoft Access, dBase

## Advantages
- Centralized system for multiple departments
- Reduced redundancy and improved data consistency
- Controlled access with defined user roles

## How DBMS Reduces Redundancy
- Stores information in a centralized database accessible to all users
- Uses normalization to avoid storing the same data multiple times
- Changes are made in one place and reflected everywhere

**Example:**  
Without a DBMS, a hotel might store guest details separately in reservations, billing, and contact files — duplicating data.  
With a DBMS, guest details are in one table, and other records reference it.

## Table Structure Recap
- **Row:** A complete record (collection of columns)
- **Column:** Individual attribute with a name and datatype

## Hospitality Case Study
Hotels use DBMS for:
- Booking and reservations
- Room availability tracking
- Guest profiles and preferences
- Billing and invoices
- Staff scheduling

## File Contents
- `dbms_notes.md` – Detailed notes
- `practice_questions.md` – Review questions
