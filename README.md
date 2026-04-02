# ENGR-340-FInal-Inventory-Management-System
# Inventory Management System

## Overview
This project is an inventory management system developed as a final project. The application allows users to check items in and out, track inventory availability, and manage user access through a simple interface.

The system was designed to be used in a real-world environment where multiple users can interact with shared resources efficiently. Keeping track of all items and tools used. 

---

## Features
- User check-in system using unique 9-digit IDs (Student ID)
- Item checkout and return functionality using 4-digit item codes
- Real-time inventory tracking (available vs checked-out items)
- Admin controls for managing items and approved users
- QR code generation and scanning for faster interaction
- Graphical User Interface (GUI) built with Tkinter
- Data persistence using file-based storage

---

## Technologies Used
- Python
- Tkinter (GUI)
- File I/O for data storage
- QR Code generation and scanning

---

## Project Structure
- `app.py` – Main application entry point
- `frames.py` – GUI layout and navigation between screens
- `data.py` – Handles data storage, loading, and saving
- `ui.py` – Input validation and helper functions
- `qr_utils.py` – QR code generation and scanning utilities

---

## Key Concepts Implemented
- Object-oriented programming in Python
- Event-driven programming (GUI interactions)
- File handling for persistent storage
- Input validation and error handling
- Basic user authentication (admin access)

---

## Team Members & Contributions
- Peter Vella - implemented item check-in/out system, and integrated GUI functionality
- Alex Leal
- Aileen Cerna
- Victor Reyes

---

## What I Learned
- Designing and structuring a multi-file Python application
- Building user interfaces using Tkinter
- Managing and organizing data efficiently
- Implementing real-world system logic for inventory tracking
- Improving debugging and problem-solving skills

---

## Future Improvements
- Add database support (SQL) instead of file storage
- Improve UI/UX design
- Add user authentication with login system
- Deploy as a web or mobile application
