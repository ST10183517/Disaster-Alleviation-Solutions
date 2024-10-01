Description:
This project involves the development of a web application using ASP.NET Core (MVC), which provides disaster alleviation solutions for various communities. The application is designed to allow users to engage in the following activities:

User Registration and Login: Users can register and log in securely using Azure Active Directory or other secure authentication mechanisms. Each user can manage their profiles and access various features of the platform.

Disaster Incident Reporting: Users can report incidents related to natural disasters such as floods, earthquakes, and fires in their area. The system provides a form for submitting detailed reports, which are stored in a connected Azure SQL Database. This helps authorities and organizations monitor disasters and respond quickly.

Resource Donation: Users can donate essential resources such as food, clothing, and medical supplies. A donation management system is in place to track donations and facilitate the distribution of these resources to affected areas.

Volunteer Management: Volunteers can register through the platform, view available tasks, and track their contributions to relief efforts. The system enables communication between volunteers and administrators, helping to streamline volunteer efforts during disasters.

Contact and About Pages: Additional pages include an About Us section detailing the mission and vision of the disaster alleviation organization, and a Contact Us section that allows users to send messages or inquiries.

Technologies Used:
ASP.NET Core MVC: For building the web application with Model-View-Controller architecture.
Azure SQL Database: To store all data related to donations, incident reports, user information, and volunteer activities.
Entity Framework Core: For database interaction and migrations.
Azure Active Directory: For secure user authentication.
Bootstrap: For responsive design and styling.
Database Design:
Each core feature of the application is backed by a set of database tables in Azure SQL, which are created and managed using Entity Framework Core. Key tables include:

Donations: Tracks the types and quantities of resources donated and their distribution locations.
Incidents: Records user-reported disaster incidents, including type, location, and description.
Reports: Stores general reports submitted by users or admins.
Contacts: Handles incoming user messages via the contact form.
Users and Volunteers: Stores user profile information, including volunteer skills and task assignments.
Key Functional Requirements:
Secure user authentication with registration and login.
A user-friendly interface for reporting disasters.
A donation form to submit and track donations.
Volunteer registration and management system.
Connection to an Azure SQL Database to store data for all features.
Deliverables:
Functional ASP.NET Core Web Application with all specified pages and features.
Azure SQL Database connection and proper configuration for all forms and data models.
Responsive Design for a seamless experience across all devices.
Entity Framework Migrations to handle database schema changes.
