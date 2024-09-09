# Hotel Management System

## Overview
The **Hotel Management System** is a simple SQL-based project designed to manage hotel bookings. It includes tables for guests, rooms, and reservations, as well as basic CRUD operations (Create, Read, Update, Delete).

## Features
- Manage hotel guests' details.
- Manage room availability and prices.
- Track reservations and ensure rooms are booked only when available.
- Update and delete reservations easily.
- List available rooms for a specific time period.
  
## Table Structure
### Guests Table
Stores guest information:
- **id_guest**: Unique identifier for the guest.
- **name**: Guest's name.
- **phone**: Guest's phone number.
- **email**: Guest's email.

### Rooms Table
Stores room details:
- **id_room**: Unique identifier for the room.
- **number**: Room number.
- **type**: Type of room (e.g., Single, Double, Suite).
- **price**: Room price per night.

### Reservations Table
Tracks room reservations:
- **id_reservation**: Unique reservation identifier.
- **id_guest**: Guest identifier (foreign key).
- **id_room**: Room identifier (foreign key).
- **checkin_date**: Check-in date.
- **checkout_date**: Check-out date.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hotel-management-system.git
