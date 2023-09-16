# <img width="252" alt="image" src="https://github.com/AlokSgupta/Road-Warrior-TRS/assets/13452049/f53da59c-a6e5-4320-b26f-e16fab7f2b67"> Road-Warrior-TRS - O'Reilly Architectural Katas 2023
Team Gensights presentation for Katta 2023 challange. 

# Problem
A new startup wants to build the next generation online trip management dashboard to allow travelers to see all of their existing reservations organized by trip either online (web) or through their mobile device.

  - Poll email looking for travel-related emails Filter and whitelist certain emails
  - The system must interface with the agency’s existing airline, hotel, and car rental interface system to update travel details (delays,cancellations, updates, gate changes, etc.).
  - Customers should be able to add, update, or delete existing reservations manually as well.
  - Items in the dashboard should be able to be grouped by trip, and once the trip is complete, the items should automatically be removed from the dashboard.
  - Users should also be able to share their trip information by interfacing with standard social media sites or allowing targeted people to view your trip.
  - Provide end-of-year summary reports for users with a wide range of metrics about their travel usage
  - Road Warrior gathers analytical data from users trips for various purposes - travel trends, locations, airline and hotel vendor preferences, cancellation and update frequency, and so on.
  - must integrate seamlessly with existing travel systems (i.e, SABRE, APOLLO)
  - Must integrate with preferred travel agency for uick problem resolution (help me!)

# Non-functional Requirements
- Users:
  - 2 Million active users/week
  - Total registered user - 15 M

- Updates must be in the app within 5 minutes of an update (better than the competition)
- Richest user interface possible across all deployment platforms
- must work internationally
- Users must be able to access the system at all times (max 5 minutes per month of unplanned downtime)
- Travel updates must be presented in the app within 5 minutes of generation by the source
- Response time from web (800ms) and mobile (First-contentful paint of under 1.4 sec)

# Solution architecture
Proposed complete solution can be found here [Road Warrior - Solution Architecure](https://github.com/AlokSgupta/Road-Warrior-TRS/blob/main/Gensights.Architecture.Presentation-Katta2023.pdf)


# Team
Name: Gensights
Members: 
  - [Alok Gupta](https://www.linkedin.com/in/enggalok/)
  - [Kiran Vangala](https://www.linkedin.com/in/divya-gangula/)
  - [Divya Gangula](https://www.linkedin.com/in/kiran-vangala-9155ab10/)


#References
- [Modern Payment Gatwway](https://www.redhat.com/architect/portfolio/detail/12-integrating-a-modern-payments-architecture)
- [Software Architecture Pattern](https://learning.oreilly.com/library/view/software-architecture-patterns/9781098134280/)
- [Mastering Patterns in Event-Driven Architecture](https://learning.oreilly.com/live-events/mastering-patterns-in-event-driven-architecture/0636920064167/)
- [Playlist](https://learning.oreilly.com/playlists/a8b481fb-1232-4c84-be62-48bed4c517fa/)
