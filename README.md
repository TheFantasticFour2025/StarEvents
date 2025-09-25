# Project File Structure & MVC Architecture of the Star Evnts Tickets Booking System

This document provides an overview of the folder and file organization of the StarEvents Online Event Ticketing System, highlighting how the project follows the Model-View-Controller (MVC) architecture.

---

## MVC Architecture Overview

- **Model:** Represents the application's data and business logic. Models are used to manage the data, validation, and rules of the application.
- **View:** Handles the display and user interface. Views are responsible for rendering HTML and presenting data to the user.
- **Controller:** Acts as an intermediary between Models and Views. Controllers handle user input, interact with models, and select views to render.

---

## Folder Structure

```
StarEventsTicketSystemV2/
├── Controllers/         # Contains all controller classes (C in MVC)
│   └── HomeController.cs
│   └── ...
├── Models/              # Contains all model classes (M in MVC)
│   └── RegisterViewModel.cs
│   └── LoginViewModel.cs
│   └── ...
├── Views/               # Contains all Razor views (V in MVC)
│   ├── Home/
│   │   └── Index.cshtml
│   │   └── ...
│   ├── Shared/
│   │   └── _Layout.cshtml
│   │   └── ...
│   └── ...
├── wwwroot/             # Static files (CSS, JS, images)
│   ├── css/
│   ├── js/
│   ├── images/
│   └── ...
├── appsettings.json      # Application configuration
├── Program.cs            # Application entry point
└── StarEventsTicketSystemV2.csproj  # Project file
```

---

## How Files Are Categorized

- **Controllers/**: Contains all controllers, each managing a specific part of the application's logic and routing (e.g., `HomeController.cs` for home page logic).
- **Models/**: Contains data models and view models, defining the structure and validation of data used throughout the application (e.g., `RegisterViewModel.cs`).
- **Views/**: Contains Razor view files organized by feature or controller, responsible for rendering the UI (e.g., `Views/Home/Index.cshtml`).
- **wwwroot/**: Contains all static assets such as CSS, JavaScript, and images, used for styling and client-side functionality.
- **Shared Views**: The `Views/Shared/` folder contains layout and partial views used across multiple pages (e.g., `_Layout.cshtml`).

---

This structure ensures a clear separation of concerns, maintainability, and scalability, following best practices of the MVC pattern in ASP.NET Core projects.

