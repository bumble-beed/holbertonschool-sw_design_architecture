## Problem — Library Loan System

A small library wants to manage its books and users.

The system must allow the library to:
- store information about books
- register users
- create loans when a user borrows a book

#### System description
The system revolves around a Library that manages books, users, and loans.

Each Book has:
- a title
- an author
- a state indicating whether it is available or not (true/false)

Each User has:
- a name
- an email

When a user borrows a book, a Loan is created.

Each Loan contains:
- a start_date
- an end_date

#### System behavior

The Library must be able to:
- add_book to its collection
- register_user
- create_loan when a user borrows a book

When a loan is created:
- the selected book must no longer be available
- the loan must reference the book and the user involved

A Book must be able to:
- mark_as_unavailable
- mark_as_available

A Loan must be able to:
- close_loan

When a loan is closed:
- the associated book becomes available again

###### Important note

All the required information to build your diagrams is contained in this description.

You must extract:
- class names
- attributes
- methods
- relationships
- multiplicities

The names used in your diagrams must match exactly the ones provided in the problem.

Do not introduce additional elements.
