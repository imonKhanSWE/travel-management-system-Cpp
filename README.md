# <u>Travel Management System (C++)</u>

A beginner-to-intermediate Travel Management System implemented in C++ using Object-Oriented Programming.  
Features: manage customers, cabs, hotel packages, bookings, and billing with file-based persistence.

## Features
- Manage Customers — GetDetails(), ShowDetails() (saved to text files)
- Manage Cabs — cab choices, kilometers, cost, CabDetails()
- Manage Bookings — hotel selection, packages, HotelDetails()
- Billing — compute cab & hotel charges, PrintBill() (save receipt to data/receipt.txt)
- Persistent storage: data/old-customers.txt and per-session receipt.txt

## Build & Run
Prerequisite: g++ (or any C++ compiler supporting C++11+).
Use Visual Studio Code to run this project.

## <u>Sample usage</u>:

Start program:

Choose Manage Customers → add new customer (ID, name, age, address)

Choose Cabs → select cab, enter distance → cost calculated

Book Hotel → choose package → hotel cost added

Billing → print and save bill to data/receipt.txt, and append customer to data/old-customers.txt

## <u> Data files </u>

data/receipt.txt — stores current customer's billing details

data/old-customers.txt — appended list of all customers who used the system
