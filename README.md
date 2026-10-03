# Movie Theater Ticket Kiosk

This project is a simple self-service ticket kiosk for a movie theater. Customers can look at the movies and showtimes that are available, pick an open seat, buy a ticket, and get a confirmation at the end. The kiosk also has to make sure the same seat is never sold to two different people.

## Project Files

- `requirements.md` – the five requirements for the kiosk
- `diagrams/` – UML diagrams made in diagrams.net (domain model, use case, and sequence diagram)



## Expanded Use Case: Purchase Ticket

**Primary Actor:** Customer

**Precondition:** The kiosk is working and the movie the customer wants has a showtime with at least one open seat.

**Main Steps:**
1. The customer looks at the list of movies and showtimes on the kiosk.
2. The customer picks a movie and a showtime.
3. The kiosk shows the seat map with open and taken seats.
4. The customer picks an open seat.
5. The system checks that the seat is still open and holds it for the customer.
6. The kiosk shows the ticket price and the customer pays.
7. The payment goes through and the system marks the seat as sold.
8. The kiosk shows a confirmation with the movie, showtime, seat number, and ticket ID.

**Postcondition:** The ticket is saved, the seat is marked as sold for that showtime so no one else can buy it, and the customer has their confirmation.
