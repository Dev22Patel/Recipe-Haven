# Recipe Book Application

A modern, user-friendly web application for managing and organizing your favorite recipes. This digital cookbook allows users to create, store, edit, and share their cherished recipes in an elegant and intuitive interface. Built with ASP.NET Core MVC, the application provides a robust platform for food enthusiasts to maintain their culinary collection.

![Recipe List View]![Screenshot 2024-10-24 150917](https://github.com/user-attachments/assets/a1b93748-f656-4937-a20a-ba5401fa2bb4)
## 🌟 Features

### Core Functionality
- **Recipe Management**
  - Create new recipes with detailed information
  - Edit existing recipes
  - Delete unwanted recipes
  - View comprehensive recipe details

### User Interface
- **Responsive Design**
  - Clean, modern interface
  - Mobile-friendly layout
  - Intuitive navigation
  - Search functionality for quick recipe access

### Recipe Details
- Title and Description
- Ingredient Management
- Step-by-step Instructions
- Image Upload Capability

## 🛠️ Technologies Used

- **Backend Framework**
  - ASP.NET Core MVC 7.0
  - Entity Framework Core 7.0
  - SQL Server 2019

- **Frontend Technologies**
  - Bootstrap 5.0
  - HTML5
  - JavaScript

- **Development Tools**
  - Visual Studio 2022
  - Git for version control

## ⚙️ Prerequisites

Before running this application, ensure you have the following installed:

1. [.NET 7.0 SDK](https://dotnet.microsoft.com/download/dotnet/7.0)
2. [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
3. [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) (recommended) or [VS Code](https://code.visualstudio.com/)

## 🚀 Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/recipe-book.git
   ```

2. **Update Database Connection**
   - Open `appsettings.json`
   - Modify the connection string to match your SQL Server instance

3. **Apply Database Migrations**
   ```bash
   add-migration InitialCreate
   update-database
   ```

## 📸 Application Screenshots

### Manage Own Recipe
![Post Management] ![Screenshot 2024-10-24 150937](https://github.com/user-attachments/assets/86f69e82-c5e9-419c-8956-3185ab272813)
*Manage Created Receipe*

### Add Recipe
![Add Recipe]![Screenshot 2024-10-24 150854](https://github.com/user-attachments/assets/ff8f5574-25b2-4130-acca-8665af2b1faf)
*Create new recipes with our intuitive form interface.*

### Edit Recipe
![Edit Recipe]![Screenshot 2024-10-24 150950](https://github.com/user-attachments/assets/9229894b-4a1f-491e-bbcd-99b1dbe5232c)
*Easily modify your recipes with our user-friendly edit interface.*

### Delete Confirmation
![Delete Recipe]![Screenshot 2024-10-24 151012](https://github.com/user-attachments/assets/781f7df3-7220-4c2d-aff6-789de1e772cc)
*Safe deletion with confirmation dialog to prevent accidental removals.*

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 👥 Authors

* **Dev Patel** - **Utsav Patel** *

## 📞 Contact

DevPatel   - notrealdev2211@gmail.com
UtsavPatel - 2004patelutsav@gmail.com
