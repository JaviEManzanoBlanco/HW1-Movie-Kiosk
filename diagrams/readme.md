# Folder for diagrams

# UML Domain Model
The domain model is meant to show how the domain classes of Movie, Showtime, Seat, Ticket, Customer, and Purchase are related.

# Use Case Diagram
The use case Diagram is meant to show what use cases the Customer Actor has with the system.

# Sequence Diagram
The sequence diagram is meant to show how the Primary Actor (Customer) submits a purchase request with purchase information such as a credit card, name, phone number, and ticket details. The Kiosk communicates the ticket details and purchase information to the Ticket Service which will pass the purchase information to the payment service and receive a confirmation. The Ticketing service will then update the database with the new ticket details, and then pass the ticket details and confirmation back to the kiosk which will present the customer with the ticket details and confirmation.
