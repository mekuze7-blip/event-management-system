# Event Management System (EMS)

A JavaFX desktop application for managing schedules, events, and automated notifications (SMS/Email).

## 🚀 Getting Started

### Prerequisites
1. **Java JDK 25** or higher.
2. **Maven 3.9+**.
3. **MySQL Server 8.0**.

### 🛠️ Installation Steps for Team Members

1. **Clone the Repository**
   ```bash
   git clone https://github.com/mekuze7/event-management-system.git
   cd event-management-system
   ```

2. **Database Setup**
   - Open MySQL Workbench or your terminal.
   - Run the script `setup-database.sql` located in the project root.
   - This creates the `event_management` database and the `mekuze7` admin user.

3. **Configuration (Important!)**
   - Locate `ems_settings.properties.example` in the project folder.
   - Copy and rename it to `ems_settings.properties`.
   - Open the file and enter your local MySQL password and API keys.
   - *Note: This file is ignored by Git to keep passwords secure.*

4. **Run the Application**
   ```bash
   mvn javafx:run
   ```

## 🔑 Default Login
- **Username:** `mekuze7`
- **Password:** `admin123`

## 🤝 Collaboration Workflow
1. Always pull latest changes:
   ```bash
   git pull origin main
   ```
2. Make your changes.
3. Commit and push:
   ```bash
   git add .
   git commit -m "Description of changes"
   git push origin main
   ```