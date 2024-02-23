# CNC_DB

### Purpose of the App:
- To track inventory for a small company, enabling efficient management of products moving from the warehouse for job use.

### Target Users:
- **Warehouse Workers:** For checking out products from the warehouse using a barcode scanner.
- **Office Worker(s):** Responsible for data entry and inventory management.
- **Supervisor:** Needs access to inventory reports for oversight and decision-making.

### Key Features and Functionalities:

1. **Web-Based Interface:** Hosted on a local server, accessible within the company network.
2. **Barcode Scanning:** To facilitate easy and accurate "check out" of parts used by workers.
3. **User Management:**
   - Multiple roles and access levels: Warehouse workers, office workers, and supervisors.
   - Authentication system for login and session management.
4. **Inventory Management:**
   - Add, edit, and delete inventory items.
   - Track current stock levels and update them based on check-outs and restocks.
5. **Data Entry and Management:**
   - Interface for office workers to input new inventory items, update existing ones, and manage supplier information.
   - Ability to import data from spreadsheets or other formats to ease the transition to the app.
6. **Reporting:**
   - Generate reports on inventory levels, usage patterns, and restocking needs.
   - Custom reports for the supervisor to monitor inventory status and make informed decisions.
7. **Supplier Management:** Track and manage supplier information linked to inventory items.

### Technical Requirements:
- **Open-Source Database:** Consider using PostgreSQL or MySQL for the backend database.
- **Backend Framework:** Depending on your preference and experience, Node.js with Express, Django, or Flask are good options for creating RESTful APIs.
- **Frontend Framework:** React or Angular for building a dynamic and responsive user interface.
- **Barcode Scanning Integration:** Research libraries or SDKs compatible with web applications for integrating barcode scanning functionality.

### Next Steps:
- **Database Design:** Start by defining the data model, including tables for inventory items, users, roles, transactions, and suppliers.
- **Technology Stack Decision:** Finalize the choices for frontend, backend, and database technologies based on team skills, project requirements, and future scalability.

Techlogies to use:
PostgreSQL
JSON
Python
Flask
HTML
CSS

Checklist:
Requirements Gathering and Planning
Technology Setup
Database Design and Implementation
Backend Development
Frontend Development
Testing
Deployment
Training and Documentation
Maintenance and Updates

DB info:
Server name: CNC
Database name: CNC_DB
User: Admin
Pass: Admin99
