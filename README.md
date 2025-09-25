# StarEvents Online Event Ticketing System

## Scenario

You are a software engineer at XYZ Pvt Ltd. StarEvents Pvt Ltd, a leading event organizer in Sri Lanka, has commissioned the development of an Online Event Ticketing Web Application. The system enables users to view and book tickets for concerts, theatre shows, and cultural events, while providing event organizers and administrators with powerful management and reporting tools.

---

## Features

- **User Registration & Login:** Secure sign-up, login, and profile management for customers and organizers.
- **Event Management:** Organizers can create, update, and manage events with details, images, and ticket pricing.
- **Event Browsing & Search:** Customers can search and filter events by category, date, or location.
- **Online Ticket Booking:** Customers can purchase tickets using integrated online payment gateways.
- **QR-Coded E-Tickets:** System generates QR-coded e-tickets for secure entry validation.
- **Admin Dashboard:** Admins can monitor system activity, manage users, and generate comprehensive reports.
- **Promotions & Loyalty:** Support for promotional discounts and loyalty points for customers.
- **Real-Time Sales Tracking:** Organizers can track ticket sales and revenue in real time.
- **Comprehensive Reporting:** Admins can generate sales, user, and event reports.

---

## System Usage

### For Customers
- Register and log in to your account.
- Browse upcoming events, filter by category, date, or location.
- View event details and book tickets online.
- Make secure payments and receive QR-coded e-tickets via email.
- Use e-tickets for event entry.

### For Event Organizers
- Log in as an organizer.
- Create new events with details, images, and ticket pricing.
- Update or manage existing events.
- Monitor ticket sales and revenue in real time.
- Access sales and revenue reports.

### For Administrators
- Log in as an admin.
- Monitor all system activity and manage users.
- Generate and download sales, user, and event reports.
- Oversee event listings and promotional campaigns.

---

## Installation Guide

### Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- [MongoDB](https://www.mongodb.com/try/download/community) (if using MongoDB for data storage)
- [Node.js & npm](https://nodejs.org/) (for front-end asset management, if needed)
- Git

### Steps

1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/StarEventsTicketSystemV2.git
   cd StarEventsTicketSystemV2
   ```

2. **Configure the Database**
   - Ensure MongoDB is running locally or update the connection string in `appsettings.json` to point to your MongoDB instance.

3. **Restore Dependencies**
   ```sh
   dotnet restore
   ```

4. **Build the Project**
   ```sh
   dotnet build
   ```

5. **Run the Application**
   ```sh
   dotnet run --project StarEventsTicketSystemV2/StarEventsTicketSystemV2.csproj
   ```
   - The application will start on `https://localhost:5001` or the port specified in your launch settings.

6. **Access the Application**
   - Open your browser and navigate to `https://localhost:5001` (or the specified port).

---

## Folder Structure

```
StarEventsTicketSystemV2/
├── Controllers/
├── Models/
├── Views/
├── wwwroot/
├── appsettings.json
├── Program.cs
└── StarEventsTicketSystemV2.csproj
```

---

## Technologies Used

- ASP.NET Core MVC (.NET 8.0)
- MongoDB (NoSQL Database)
- Razor Views
- Bootstrap (UI Framework)
- Entity Framework Core (if used)
- QR Code Generation Library

---

## Contribution

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## License

This project is licensed under the MIT License.

---

## Contact

For any inquiries or support, please contact the development team:
Diosn Methvin
Ralph Shenal
Wishva Kothalawala
Dhananjana Thathsarani

---
