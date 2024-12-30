# NoteTaker Web Application

## Description
NoteTaker is a Java-based web application for creating, managing, and organizing notes. It is built using JSP, Servlets, and Hibernate ORM with MySQL as the database.

---

## Project Structure
### Key Components:
1. **Entities** (`src/main/java/com/entities`): Represents data models like `Note.java`.
2. **Helper Classes** (`src/main/java/com/helper`): Contains utility classes like `FactoryProvider.java` for Hibernate session factory.
3. **Servlets** (`src/main/java/com/servlets`): Includes servlets for CRUD operations:
    - `SaveNoteServlet.java` to save notes.
    - `DeleteServlet.java` to delete notes.
    - `UpdateServlet.java` to update notes.
4. **Frontend JSP Pages** (`src/main/webapp`): Contains JSP files for UI:
    - `add_notes.jsp`: Add a new note.
    - `all_notes.jsp`: View all notes.
    - `edit.jsp`: Edit a note.
    - `index.jsp`: Home page.
    - `navbar.jsp`: Common navigation bar for all pages.

5. **Configuration File** (`src/main/resources`):
    - `hibernate.cfg.xml`: Hibernate configuration file for database connectivity.

---

## Prerequisites
- Java Development Kit (JDK) 8 or higher.
- Apache Tomcat 9 or higher.
- MySQL Server (with a database named `NoteTaker`).
- Maven (for dependency management).

---

## Setup and Execution
1. **Clone the Repository**
   ```bash
   git clone https://github.com/<your-username>/notetaker.git
   cd notetaker
