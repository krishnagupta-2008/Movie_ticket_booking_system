# Movie Ticket Booking System

A modular, console-based movie ticket booking system developed in C++ using object-oriented design.

## Features

- Display movies, languages, durations, and show timings
- Display cinema screens and seat layouts
- Book and cancel seats for a selected show
- Support Silver, Gold, and Platinum seat categories
- Calculate booking prices by seat category
- Support UPI, card, and cash payment options
- Print booking tickets after successful payment
- Validate user input and handle invalid selections safely

## Project Layout

- `CODES/` - C++ source files and the program entry point
- `CLASS_DIAGRAM.jpeg` - class diagram
- `SEQUENCE_DIAGRAM.jpeg` - sequence diagram
- `MTBS_report.pdf` - project report
- `OUTPUT.pdf` - sample output

## Build and Run

Compile `main.cpp`; it includes the class implementation files in `CODES/`.

```bash
g++ -std=c++17 CODES/main.cpp -o movie_booking
./movie_booking
```

On Windows:

```powershell
g++ -std=c++17 CODES/main.cpp -o movie_booking.exe
.\movie_booking.exe
```

## OOP Concepts Demonstrated

- **Encapsulation:** Classes protect their data through private members and public methods.
- **Abstraction:** Payment behavior is defined through a common interface.
- **Inheritance:** Payment methods share the payment abstraction.
- **Polymorphism:** The selected payment method is resolved at runtime.
- **Composition:** A cinema contains screens, and screens contain seats.
- **Association:** Shows use movie and screen objects to represent bookings.
