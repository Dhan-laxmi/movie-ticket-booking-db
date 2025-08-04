# Movie Ticket Booking Database

This project contains the database schema and ER diagram for a movie ticket booking system.

## Tables

- `Users`: Stores user information
- `Movies`: Movie details
- `Theaters`: Theater locations
- `Showtimes`: Movie schedule (date, time, location)
- `Bookings`: Ticket bookings by users

## Relationships

- A movie has many showtimes
- A theater has many showtimes
- A user can make many bookings
- A showtime can have many bookings

## Files Included

- `movie_ticket_schema.sql` – SQL script to create tables and keys
- `MovieTicket_ER_Diagram.png` – Visual diagram of the database

## Tools Used

- MySQL Workbench
