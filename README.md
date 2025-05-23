#  Bus-Reservation-and-Pass-Creation-System
![Screen shots](https://cloud.githubusercontent.com/assets/22594110/24895423/2a5eaa08-1e45-11e7-8cd3-3f5d51cf54da.gif)
# 🚌 Bus Reservation and Pass Creation System

This system allows users to book bus tickets and create bus passes online, eliminating the need to physically visit the bus terminal. It simplifies the bus ticketing process and pass management.

## 📌 Features

- Book bus tickets easily from anywhere
- Create bus passes for regular travel
- View and manage bookings and passes
- User-friendly interface with Bootstrap and jQuery

## 🛠️ Technologies Used

| Layer         | Technology              |
|---------------|-------------------------|
| Backend       | JSP, Servlet            |
| Frontend      | Bootstrap, HTML, jQuery |
| Database      | MySQL                   |
| Architecture  | MVC (Model-View-Controller) |
| Development   | Eclipse IDE             |
| Server        | Apache Tomcat 7         |

## 📁 Directory Structure

```
Bus-Reservation-and-Pass-Creation-System/
├── WebContent/                # Frontend files: HTML, CSS, JS, Bootstrap assets
│   ├── css/
│   ├── js/
│   ├── images/
│   └── *.html                 # Web pages
├── src/                      # Java source files (Servlets, Controllers)
│   └── com/                  # Package structure for Java classes
│       └── yourpackage/      # Your Java packages
├── WEB-INF/                  # Web app config files
│   ├── web.xml               # Deployment descriptor
│   ├── lib/                  # External JAR libraries
│   └── classes/              # Compiled classes
├── database.sql              # MySQL database schema and seed data
├── .project                  # Eclipse project settings
├── .classpath                # Eclipse classpath settings
└── README.md                 # Project documentation
```

## ⚙️ Getting Started

### Prerequisites

- Java JDK (version 8 or above)
- Apache Tomcat 7 server
- MySQL Server
- Eclipse IDE (or any Java EE compatible IDE)

### Installation and Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/saurabhrathod35/Bus-Reservation-and-Pass-Creation-System.git
   cd Bus-Reservation-and-Pass-Creation-System
   ```

2. **Setup the Database**

   - Open MySQL and create a database (e.g., `bus_system`).
   - Import the provided `database.sql` file to create tables and seed initial data.

3. **Configure Database Connection**

   - Update the database connection settings in your project (usually in a config file or servlet code).
   - Example JDBC URL:  
     ```
     jdbc:mysql://localhost:3306/bus_system
     ```
   - Provide your MySQL username and password.

4. **Import Project in Eclipse**

   - Open Eclipse and import the project as an existing Dynamic Web Project.
   - Ensure Apache Tomcat 7 is configured as the server runtime.

5. **Run the Application**

   - Start Tomcat server from Eclipse.
   - Access the app in your browser at:  
     ```
     http://localhost:8080/Bus-Reservation-and-Pass-Creation-System/
     ```

## Usage

- Navigate to the booking page to reserve bus tickets.
- Use the pass creation section to apply for travel passes.
- Manage existing bookings and passes through the user dashboard.

## Author

**Saurabh Rathod**  
GitHub: [@saurabhrathod35](https://github.com/saurabhrathod35)

## License

This project is licensed under the MIT License.  
See the [LICENSE](LICENSE) file for details.

### 🔧 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/saurabhrathod35/Bus-Reservation-and-Pass-Creation-System.git
