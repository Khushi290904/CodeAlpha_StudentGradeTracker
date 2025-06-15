Java Application Suite

This repository contains three Java console-based applications: a Student Grade Tracker, a Stock Trading Platform, and a Hotel Reservation System. Each program is designed to demonstrate core Java programming concepts, including data structures, file I/O, input validation, and object-oriented design.

Table of Contents





Student Grade Tracker



Stock Trading Platform



Hotel Reservation System



Requirements



Setup

Student Grade Tracker

Overview

The Student Grade Tracker allows teachers to manage student grades by adding student records, calculating statistics (average, highest, and lowest scores), and displaying all student data. It uses ArrayList to store student names and grades, with data stored in memory during execution.

Features





Add students with names and grades (0-100).



Calculate and display class statistics (average, highest, and lowest scores with corresponding student names).



List all students and their grades.



Input validation for grades and menu options.

Usage





Run GradeTracker.java.



Select from the menu:





1: Add a student (enter name and grade).



2: Display class statistics.



3: List all students.



4: Exit.



Follow prompts to input data.

Notes





Grades are validated to be between 0 and 100.



Data is not persisted between sessions.



File: GradeTracker.java

Stock Trading Platform

Overview

The Stock Trading Platform simulates a stock market where users can view market data, buy/sell stocks, and track their portfolio. It features four predefined stocks with simulated price fluctuations and uses file I/O for portfolio persistence.

Features





Display market data for four stocks (AAPL, GOOGL, MSFT, AMZN) with random price changes (±$5).



Buy and sell stocks with validation (sufficient funds, valid symbols, etc.).



Track portfolio (cash balance, holdings, average purchase price, and total value).



Persist portfolio data using serialization (portfolio.dat).

Usage





Run StockTradingPlatform.java.



Select from the menu:





1: View market data (symbols, company names, prices, changes).



2: View portfolio (cash, holdings, total value).



3: Buy stocks (enter symbol and quantity).



4: Sell stocks (enter symbol and quantity).



5: Exit.



Follow prompts for inputs (e.g., stock symbols, quantities).

Notes





Initial cash balance is $10,000.



Portfolio data is saved in portfolio.dat.



Stock prices are simulated and not based on real market data.



File: StockTradingPlatform.java

Hotel Reservation System

Overview

The Hotel Reservation System allows users to search for available rooms, make reservations, and view booking details. It supports three room categories (Standard, Deluxe, Suite) and simulates payment processing, with data persistence using file I/O.

Features





Search available rooms by check-in/check-out dates and optional category.



Make reservations with guest details, room selection, and date validation.



Simulate payment processing (validates 16-digit credit card number).



View booking details using a unique reservation ID.



Persist room and reservation data (rooms.dat, reservations.dat).

Usage





Run HotelReservationSystem.java.



Select from the menu:





1: Search available rooms (enter dates and optional category).



2: Make a reservation (enter guest name, room number, dates, payment details).



3: View booking details (enter reservation ID).



4: Exit.



Follow prompts for inputs (e.g., dates in yyyy-MM-dd, room numbers).

Notes





Room categories: Standard ($100/night, rooms 101-110), Deluxe ($200/night, rooms 201-205), Suite ($350/night, rooms 301-303).



Dates must be in yyyy-MM-dd format; check-in cannot be in the past, and check-out must be after check-in.



Data is saved in rooms.dat and reservations.dat.



Payment processing is simulated (no real transactions).



File: HotelReservationSystem.java

Requirements





Java Development Kit (JDK) 8 or higher.



A Java IDE (e.g., IntelliJ IDEA, Eclipse) or command-line tools for compilation and execution.
