# locallibrary_go
locallibrary implementation in go - API with postgres DB

## Project Idea

This is a library system built using go as a RESTful API. Functions as a physical library would. It stores information about books and book instances, their authors etc. Normal users can request to borrow books, these requests are then approved by librarians who are themselves users. All endpoints to the system are exposed through a REST interface

## Functionality
- Keep track of books, bookinstance and authors
- Allow users to borrow books - users need to register before they can start borrowing books
- A request to borrow a book is first approved by a librarian before users can be allowed to borrow the book
-

## Additional Functionality
- The system should send a text message to users whose due date of returning a book is past
