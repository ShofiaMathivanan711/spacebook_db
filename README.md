## Spacebook – Data Model

### Project Overview

This folder contains the database design and SQL scripts for the **Spacebook application**, an office room and hotseat booking system. It organizes the database structure and data required to manage locations, offices, modules, employees, rooms, facilities, seats, bookings, and notifications.

### Folder Structure

```text
Data Model/
├── DDL/
│   ├── Bookings.sql
│   ├── Employees.sql
│   ├── Facilities.sql
│   ├── HotSeatBookings.sql
│   ├── Locations.sql
│   ├── Modules.sql
│   ├── Notifications.sql
│   ├── Offices.sql
│   ├── Roles.sql
│   ├── RoomFacilities.sql
│   ├── RoomTypes.sql
│   ├── Rooms.sql
│   └── Seats.sql
├── DML/
│   ├── Bookings_data.sql
│   ├── Employees_data.sql
│   ├── Facilities_data.sql
│   ├── HotSeatBookings_data.sql
│   ├── Locations_data.sql
│   ├── Modules_data.sql
│   ├── Notifications_data.sql
│   ├── Offices_data.sql
│   ├── Roles_data.sql
│   ├── RoomFacilities_data.sql
│   ├── RoomTypes_data.sql
│   ├── Rooms_data.sql
│   ├── Seats_data.sql
│   └── Update_data.sql
└── ER Diagram.drawio
```

### Database Components

| Entity          | Description                             |
| --------------- | --------------------------------------- |
| Locations       | Stores office location information.     |
| Offices         | Represents offices within locations.    |
| Modules         | Organizes office modules or areas.      |
| Employees       | Stores employee information.            |
| Roles           | Defines application roles.              |
| Rooms           | Stores meeting room details.            |
| RoomTypes       | Categorizes rooms by type.              |
| Facilities      | Stores available room facilities.       |
| RoomFacilities  | Associates rooms with their facilities. |
| Bookings        | Stores room booking information.        |
| Seats           | Stores hotseat or seat details.         |
| HotSeatBookings | Stores hotseat booking information.     |
| Notifications   | Stores notification details.            |

### DDL – Data Definition Language

The `DDL/` folder contains SQL scripts used to define the database structure, including table creation and related database objects.

### DML – Data Manipulation Language

The `DML/` folder contains SQL scripts used to insert and update data in the database.

* Individual `*_data.sql` files contain data scripts for their respective entities.
* `Update_data.sql` contains update-related SQL statements.

### Entity-Relationship Diagram

The `ER Diagram.drawio` file represents the database entities and their relationships. It can be opened and edited using [draw.io (diagrams.net)](https://app.diagrams.net/).

### Technologies and Tools

* **SQL** – Database definition and data manipulation.
* **Git and GitHub** – Version control and source-code management.
* **draw.io (diagrams.net)** – Entity-relationship diagram design.

### How to Use

1. Clone or download the repository.
2. Navigate to the `Data Model/` folder.
3. Review the ER diagram to understand the database structure and relationships.
4. Execute the DDL scripts in the appropriate dependency order.
5. Execute the DML scripts after confirming that the required tables exist.
6. Verify the inserted or updated data.

**Note:** Confirm the database connection, foreign-key dependencies, and execution order before running the scripts. Test data-modification statements in a development or test database first.


