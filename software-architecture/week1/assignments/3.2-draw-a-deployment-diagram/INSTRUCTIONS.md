# Guidelines for the assignment

## Review these Lectures to aid you on your assignment:  

3.1.3 - Component Diagrams

## Recap

For those of you who are new to this specialization, the code base you will be working with involves an Android application, a Web application, and remote database. Capstone assignments in the Software Architecture course build off the updated version of the Android app from the earlier Design Patterns course with added functionality.

In the application’s current state:

- A user of the app is able to create and edit a profile with a unique username and any email. (New)
- A user of the app is able to login and logout. (New)
- An owner is able to record the items they own and wish to share.
- A bidder is able to place bids on items they wish to borrow from other users, which changes the status of the - - item to “Bidded”. (New)
- An owner is able to accept a bid and lend the item to the bidder, which changes the status of the item to “Borrowed”. (New)
- An owner may change the status of an item they own from “Borrowed” to “Available” when the item is no longer being borrowed.
- An owner may view: all of their items; their “Available” items; their “Bidded” items; or, their “Borrowed” items.
- A borrower may view a list of items they are borrowing. (New)
- A user of the app is able to search a list of all “Available” and “Bidded” items by keywords. (New)
- An owner is able to view the profile of a borrower who is borrowing one of their items. (New)

## How to create your assignment

- In this assignment you are to assume that the mobile application (described above) stores its data in a remote database (rather than locally -- as the current version of the app actually does.)
- To access this remote database, the mobile app sends an HTTP request to the remote server that matches the remote server’s provided interface.
- The web server parses the HTTP request to determine its type, then passes the data along to the application server. The data the web server provides the application server must match the application server’s provided interface.
- Next, the application server parses the request. Depending on the request, it either fetches data from the database or modifies the database using the database’s provided interface.
- In addition to a mobile app, there is also a web app which can be accessed through a web browser. The web application, like the mobile application, is able to access the remote database by making a request to the web server.
- Based on this description make a UML component diagram that represents this system.

