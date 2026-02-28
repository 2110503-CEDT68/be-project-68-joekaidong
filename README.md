<<<<<<< HEAD
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/iG82Gnyy)
=======
# Project 1: Hotel Booking

## Non-Functional Requirements
* Security:
        * The system shall authenticate users using username-
password.
        * The system shall be able to keep user’s transactions
confidential.
* Performance:
        * The system shall response to a request in 3 seconds.
* Usability:
        * The system shall be used and test via Postman.

## Functional Requirements
1. The system shall allow a user to register by specifying the name, telephone number, email, and
password.
2. After registration, the user becomes a registered user, and the system shall allow the user to log in to
use the system by specifying the email and password. The system shall allow a registered user to log
out.
3. After login, the system shall allow the registered user to book up to 3 nights by specifying the date and
the preferred hotel. The hotel list is also provided to the user. A hotel information includes the hotel
name, address, and telephone number.
4. The system shall allow the registered user to view his hotel bookings.
5. The system shall allow the registered user to edit his hotel bookings.
6. The system shall allow the registered user to delete his hotel bookings.
7. The system shall allow the admin to view any hotel bookings.
8. The system shall allow the admin to edit any hotel bookings.
9. The system shall allow the admin to delete any hotel bookings.

## Schema
User: {
        id: String,
        name: String,
        tel: String,
        email: String,
        password: String
        role: String -> (admin/user)
}

Hotel: {
        id: String
        name: String,
        address: String,
        tel: String
}

Reservation: {
        date: Date
        hotel_id: String
}

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/_xCBcc1c)
>>>>>>> b5ae60f (Intial Commit)
