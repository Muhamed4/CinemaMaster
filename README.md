# **CinemaMaster**

**CinemaMaster** is an online movie ticket booking system that allows users to search for movies, check available shows, reserve seats, and make secure payments. The system offers real-time seat availability, support for advanced search filters, and ticket bookings across multiple cinemas and cities. Customers can view seating arrangements, book their preferred seats, and receive notifications for new movie releases and booking confirmations.

![Cinema Master](Images/CinemaMaster.jpg)

## **Requirements and Goals:**

- List cities where affiliate cinemas are located.
- Each cinema can have multiple halls, and each hall can run one movie show at a time.
- Each movie will have multiple shows.
- Customers should be able to search for movies by title, language, genre, release date, and city name.
- After selecting a movie, the system should display cinemas running that movie and their available shows.
- Customers should be able to select a show at a specific cinema and book their tickets.
- The system should show the seating arrangement of the cinema hall, allowing customers to select multiple seats according to their preference.
- Notifications should be sent whenever a new movie is added or a booking is made/canceled.
- Payment options should include credit cards and cash, with the ability to apply discount coupons.

## **System Design** :

### **Use Case Diagram** :
- The use case diagram highlights the key interactions between users (customers, admins, front desks) and the system, including searching for movies, 
booking tickets, managing schedules, and making payments.

### **Activity Diagram** : 
- The activity diagram outlines the flow of operations within the system, including how users search for movies, book tickets, 
and complete payments.

### **Class Diagram** : 
- The class diagram shows the structure of the system's classes, their attributes, methods, and the relationships between them, 
including Movie, Cinema, Show, Booking, Customer, and more.

### **Entity Relationship Diagram (ERD)** :
- This diagram illustrates the relationships between the main entities in the CinemaMaster Booking system, 
such as Movies, Customers, Bookings, Cinemas, and Seats.


## **Features**

- Search movies by title, genre, language, release date, and city.
- Browse cinemas and available shows.
- View seating arrangements and real-time seat availability.
- Book tickets for multiple shows and reserve seats.
- Make secure payments using credit cards or cash.
- Apply discount coupons during payment.
- Receive notifications for new movie releases and booking updates.
- Admin and front desk roles for managing movie schedules and bookings.

## **Technologies Used**

- **Backend**: ASP.NET Core (C#)
- **Database**: Microsoft SQL Server
- **ORM**: Entity Framework Core for database interactions
- **API**: RESTful services built using ASP.NET Web API
- **Authentication**: Identity Framework or OAuth (for user login/signup)
- **Notifications**: Email or SMS notifications for updates (via Twilio, SendGrid, or similar service)
- **Payments**: Integrated with credit card and cash payment systems
- **Version Control**: Git with a Git Flow workflow for professional branching and collaboration.

## **Getting Started**

### **Prerequisites**
- .NET SDK (version 8.0)
- Microsoft SQL Server
- Git

### **Installation**

1. Clone the repository:

   ```bash
   git clone https://github.com/Muhamed4/CinemaMaster.git
2. Navigate to the project directory:

   ```bash
   cd CinemaMaster
3. Set up the database:

    - Configure your SQL Server instance.
    - Update the connection string in the appsettings.json file.

4. Run the application:

    ```bash
   dotnet run
5. Open the project in your browser at http://localhost:5000 (or the port specified in your settings).



### **Project Structure**

* Controllers/: Handles API requests and responses.
* Models/: Defines entities like Movie, Cinema, Show, Booking, and Customer.
* Migrations/: Handles database migrations for tracking changes.


### **Contributing**

If you'd like to contribute to this project, please follow these steps:

- Fork the repository.
- Create a new feature branch (``git checkout -b feature/your-feature-name``).
- Commit your changes (``git commit -am 'Add a new feature'``).
- Push to the branch (``git push origin feature/your-feature-name``).
- Open a pull request.