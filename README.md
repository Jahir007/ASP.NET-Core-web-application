# ASP.NET Core Web Application with User Authorization and Role Based Access control

This repository contains the source code and documentation for an ASP.NET Core web application with user authorization. The application allows users to manage contacts with different permission levels based on their roles.

## Features

- **User Authentication:** Users can register, login, and logout securely.
- **Role-Based Authorization:** Different roles (Registered Users, Managers, Administrators) have varying levels of access to contact information.
- **Custom User Management:** Extends the IdentityUser class to include custom properties like First Name, Last Name, etc.
- **Permission-Based Authorization:** Implements permission-based access control to restrict users' actions within the application.
- **Responsive UI:** Utilizes HTML and CSS for a visually appealing and user-friendly interface.

## Technologies Used

- **ASP.NET Core:** Developed the web application framework using Visual Studio and .NET capabilities.
- **C# Programming Language:** Used for server-side scripting and backend logic.
- **HTML, CSS:** Employed for front-end development to ensure responsiveness and aesthetics.
- **SQL Server Management Studio (SSMS):** Used for creating and managing the SQL Server database to ensure data integrity and security.

## Usage

1. **Clone Repository:** Clone this repository to your local machine using `git clone https://github.com/your-username/your-repository.git`

2. **Setup Database:** Use SQL Server Management Studio (SSMS) to create and manage the database. Ensure proper configuration in `appsettings.json`.

3. **Build and Run:** Open the solution file in Visual Studio and build the project. Run the application to launch it in your web browser.

4. **Register and Login:** Create a new account or login with existing credentials. Depending on your role (Registered User, Manager, Administrator), you'll have access to different features.

5. **Manage Contacts:** Based on your role, you can view, modify, or delete contact information. Managers can approve or reject contact requests.

## Contributing

Contributions are welcome! If you have any ideas for improvements or find any issues, feel free to open an issue or submit a pull request.

## License

The project "ASP.NET Core Web Application with User Authorization" is developed and maintained by Jahir007.

### MIT License

The project is licensed under the MIT License, which permits you to freely use, modify, and distribute the software under certain conditions. See the [LICENSE](LICENSE) file for details.

## Personal Note

I believe in the spirit of open collaboration and innovation. Feel free to use this project for your own purposes, whether it's learning, building upon it, or incorporating it into your projects. Let's continue to create and share knowledge together!
