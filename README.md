# Employee Management System
Desktop CRUD application using Java Swing, JDBC and MySQL.

## Features
- Add, update, delete and search employees
- Swing desktop UI
- DAO-based JDBC persistence
- Prepared statements and normalized employee table

## Run
1. Install Java 17+, Maven and MySQL.
2. Run `database.sql`.
3. Edit DB credentials in `DBConnection.java` or set `DB_URL`, `DB_USER`, `DB_PASSWORD` environment variables.
4. Run `mvn clean package` then start `com.naresh.ems.EmployeeManagementApp` from your IDE.
