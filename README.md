# Exam School Presentation with DB

This project is a web application built using **.NET MVC Core** that showcases a school's profile, events, and author information. The application features three main pages:

## Features

- **Home Page:**  
  Presents the school, highlighting its features, educational opportunities, and unique qualities. This is the main landing page for visitors to learn about the school.

- **Events Page:**  
  Displays upcoming and past school events. The events data is dynamically injected and managed through a **SQLite database**, allowing for easy updates and scalability.

- **About Page:**  
  Shares an autobiography of the author, providing background information and personal presentation to the public.

## Technologies Used

- [.NET MVC Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/overview?view=aspnetcore-7.0)
- [SQLite](https://www.sqlite.org/index.html) (for the Events data storage)

## Getting Started

### Prerequisites

- [.NET Core SDK](https://dotnet.microsoft.com/download)
- [SQLite](https://www.sqlite.org/download.html) (installed or included via NuGet)
- A code editor (such as Visual Studio or VS Code)

### Running the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pullchek/Exam-School-Presentation-with-DB.git
   cd Exam-School-Presentation-with-DB
   ```

2. **Restore dependencies:**
   ```bash
   dotnet restore
   ```

3. **Apply any pending migrations and update the database:**
   ```bash
   dotnet ef database update
   ```

4. **Run the application:**
   ```bash
   dotnet run
   ```

5. Open your browser and navigate to `http://localhost:5000` (or the port specified in your project settings).

## Project Structure

- `Controllers/` - MVC controllers for Home, Events, and About pages
- `Models/` - Entity models, including the Event model for database operations
- `Views/` - Razor views for each page
- `Data/` - Database context and migration files for SQLite

## Contributing

Contributions are welcome! Please fork the repository and open a pull request with your changes.

## License

This project is licensed under the MIT License.

---

Feel free to update this README with additional details as your project grows!
